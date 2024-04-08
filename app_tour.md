---
title: App Tour
layout: page
parent: Getting Started
nav_order: 3
---

# the **remote control**

If your phone didn't automatically forward you to the Emotiscope web app, then you can access it from the button below. **Play some funky tunes, and enjoy!** *Come back here if you want to learn more!*

[Jump To The App](https://app.emotiscope.rocks/){: .btn .btn-green }

# the **quick tour**

I've tried my best to keep Emotiscope's remote *(Remotiscope?)* as simple as possible, with only one main function to learn: **Sliders**.

If you've ever used a dimmer switch, *you already understand Sliders.*

Too dim? Pull up. Too colorful? Pull down.

You'll always see three Sliders on-screen at a given time, but you can always swipe horizontally to scroll through the **Slider Gallery**.

![GALLERY](https://github.com/lixie-labs/emotiscope-site/blob/main/img/gallery.jpg?raw=true)

Each slider can be used to customize the current light-show mode:

| Setting       | Description                                                                                                                                                                                        |
|---------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Brightness    | The brightness of your Emotiscope's LED display                                                                                                                                                  |
| Softness      | How quickly your Emotiscope's display reacts to changes; this can be used to reduce flickering effects at the cost of reaction time                                                              |
| Speed         | How quickly things on screen can move                                                                                                                                                            |
| Color         | The base color of the current mode                                                                                                                                                               |
| Color Range   | How much the color can vary from the base color                                                                                                                                                  |
| Saturation    | The intensity of the color of the display                                                                                                                                                        |
| Blue Filter   | Applies a filter to the display which limits the brightness of blue colors, similar to the look of incandenscent light bulbs that were tinted by a colored film                                  |
| Background    | The intensity of the background color                                                                                                                                                            |
| Mirror Mode   | **(toggle)** Scales the display to 1/2 size and mirrors it to be symmetrical                                                                                                                     |

# the **light-show modes**

Light-show Modes change how Emotiscope reacts to sound. Not all songs will work well with every mode, but every song has at least one that will. There's many to choose from, so here's a quick break down:

## **ANALOG**

Analog Mode simulates the movement of a analog VU meter, with dots of light reacting to the current loudness of music, wiggling to beats and vocals. Sub-pixel rendering tricks make this mode a visual treat you can't go wrong with.

<iframe class="youtube-video" src="https://www.youtube.com/embed/HZR-9pEwA5I" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## **SPECTRUM**

Spectrum Mode shows the detected strengths of all musical notes between 110 Hz and 4186 Hz (The upper 64 keys of a piano), showing chords, vibrato and even basslines in the center! (For the music geeks, that's A2 through C8!)

<iframe class="youtube-video" src="https://www.youtube.com/embed/FeMDX4kWn0s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## **OCTAVE**

Octave Mode is the same as Spectrum Mode, but all 64 notes have been wrapped into a single octave - meaning all A♭ notes are in the same position on the display, regardless of which octave they originated from.

<iframe class="youtube-video" src="https://www.youtube.com/embed/SrPG6KX4maI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## **METRONOME**

Metronome Mode is extra fancy. Your Emotiscope will synchronize itself to the beat of your music, swaying patterns back and forth exactly in time with the song. It's not only aware of what the current tempo (BPM, speed) of your music is, it also knows the magnitude of *all* tempi at a given time and displays all readings at the same time. For example, if the snare drum hits 90 beats per minute but the hi-hat hits 180 beats per minute, both patterns are detected and shown at the same time!

<iframe class="youtube-video" src="https://www.youtube.com/embed/g1X5JhoE_lc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## **SPECTRONOME**

This is actually a hybrid mode! When confidence in the tempo calculation is low, Spectrum Mode is shown, but as Emotiscope gains confidence in the beat of the music, it will fade into showing Metronome Mode instead.

<iframe class="youtube-video" src="https://www.youtube.com/embed/_y0_qLfevxY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## **HYPE**

Hype Mode is for partying it up. This is the mode for dance music and bass drops. All tempo readings are summed up into a single wave, meaning complicated patterns can emerge from the average song, which are wiggling to and fro to the beat of the music. As a rule of thumb, if it's a song you think you could generate "hype" with, it works great with this mode.

<iframe class="youtube-video" src="https://www.youtube.com/embed/m00ZpmTfyCw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## **BLOOM**

Bloom Mode is quite versatile. Dragging the speed slider all the way down makes a slowly expanding pattern that flutters to your tunes, and turning the speed slider all the way up makes for a hypnotizing dive into a psychedelic tunnel.

<iframe class="youtube-video" src="https://www.youtube.com/embed/GtlkNGFajNk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## **NEUTRAL**

Neutral Mode does nothing, but it does nothing *really well*. For occasions where you want a beautiful light bar that *doesn't* react to sound, Neutral Mode allows you to customize the colors without listening to music.

> You found the page I haven't finished yet today!
>
> Congratulations, stay tuned!

{: .warning }
While the advice in this section is likely correct in 99% of cases, ALWAYS double check the labelling and color scheme of the wires in your own LED strip to be sure that nothing will be damaged.

Once the wires are stripped, insert them into the LED terminal as shown, tightening the screws down on the wires as you go. Be sure that none of the bare wire is exposed, so that it cannot short-circuit with itself. (If you're using a 4-wire strip, be sure to hook up all four wires correctly.)

{: .highlight }
Some strips have duplicate wires for 5V and GND. These can be wired to a separate power supply, individually covered with electrical tape, or doubled-up into the corresponding terminals if you plan to power the LEDs using only the Sensory Bridge.

![SENSORY BRIDGE IS SIMPLE](https://github.com/connornishijima/sensory_bridge_docs/blob/main/img/16.jpg?raw=true)

