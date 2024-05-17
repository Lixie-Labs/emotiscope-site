---
title: The Remote Control
layout: page
parent: Getting Started
nav_order: 3
---

# the **remote control**

A web-app built by a hardware designer to be fun, responive, and ergonomic. You don't need an account, there's no ads, there's no subscription. You can save it to your homescreen via the browser's menu and it'll get an icon just like a "real" app.

![Remote Control](https://github.com/lixie-labs/emotiscope-site/blob/main/img/remote_control.jpg?raw=true)

If there's an Emotiscope on a WiFi network, any phone on that same network can control it - including your friends at the party. Just visit "**[app.emotiscope.rocks](https://app.emotiscope.rocks/)**" in any web browser to be automatically forwarded to your Emotiscope's Remote Control screen.

It's not like "smart home" devices that take a short moment to react once you've touched your screen. Emotiscope is designed with high-speed communication that allows your phone to smoothly and intuitively control Emotiscope without any perceptible delay. If you weren't already forwarded to the Emotiscope web app after WiFi setup, then you can access it from the button below:

**Play some funky tunes, and enjoy.** - [@lixielabs](https://twitter.com/lixielabs)

[Jump To The App](https://app.emotiscope.rocks/){: .btn .btn-green }

*Come back here if you want to learn more!*

# the **quick tour**

I've tried my best to keep Emotiscope's remote *(Remotiscope?)* as simple as possible, with only one main function to learn: **The Setting Gallery**.

You'll always see three settings on-screen at a given time, but you can always swipe horizontally to scroll through The Setting Gallery.

![GALLERY](https://github.com/lixie-labs/emotiscope-site/blob/main/img/gallery.jpg?raw=true)

<span style="color:#c15472">**Sliders** are pink</span>, and used smoothly control settings like brightness and color.

If you've ever used a dimmer switch, *you already understand Sliders.* Not bright enough: pull up. Too colorful: pull down. (Some sliders only appear in certain modes)

For settings that can only be turned on and off, there's <span style="color:#5897ce">**Toggles**, which are blue</span>.

All of these Sliders and Toggles can be used to endlessly customize the shows your Emotiscope produces:

| Setting             | Description                                                                                                                                                                                      |
|---------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Brightness          | The brightness of your Emotiscope's LED display                                                                                                                                                  |
| Softness            | How quickly your Emotiscope's display reacts to changes; this can be used to reduce flickering effects at the cost of reaction time                                                              |
| Speed               | How quickly patterns on screen can move (Only used in Analog and Bloom Mode)                                                                                                                     |
| Color               | The color that Emotiscope shows                                                                                                                                                                  |
| Color Range         | How much that color can vary                                                                                                                                                                     |
| Saturation          | How vibrant the colors on Emotiscope are                                                                                                                                                         |
| Warmth              | Applies a filter which limits the brightness of blue colors, giving a warm retro look                                                                                                            |
| Background          | The intensity of the background gradient                                                                                                                                                         |
| Mirror Mode         | **(toggle)** Enables a symmetrical version of the current light mode                                                                                                                             |
| Reverse Color Range | **(toggle)** Reverses the direction of the color range, meaning that if your base color is red, the color range extends towards blue instead of green.                                           |
| Auto Color Cycle    | **(toggle)** Automatically cycles the base color to the music during moments of high musical intensity                                                                                           |

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

# the **indicator lamp**

Emotiscope has a mellow yellow LED on the front, that does only three things:

- **Dim, steady** - Emotiscope is connected to WiFi and ready for use
- **Bright, steady** - You're interacting with Emotiscope through the app or touch
- **Flashing** - No WiFi connection available

![INDICATOR LAMP](https://github.com/lixie-labs/emotiscope-site/blob/main/img/indicator_lamp.jpg?raw=true)

# room **calibration**

Emotiscope can adapt to different acoustic environments by sampling the background noise. With no music playing, hit the Remove Background Noise button and one second later Emotiscope will stop responding to ambient stimuli like air conditioners or urban traffic.

# the **screensaver**

When no audio is heard for a short while, Emotiscope will gently daydream a 4-colored pattern while it awaits new tunes. You can disable this in the Top Menu if you'd like.

# the **top menu**

Up in the top menu, you'll get to the deeper settings and data about Emotiscope.

![TOP MENU](https://github.com/lixie-labs/emotiscope-site/blob/main/img/top_menu.jpg?raw=true)

## Screensaver

You can toggle whether or not Emotiscope daydreams between songs!

## Temporal Dithering

If you find you're sensitive to the high-speed (200-400Hz) color switching Emotiscope uses to draw smoother gradients, you can disable it. This reduces color reproduction from approximately 12-bit color to 8-bit.

## Calibrate Touch Sensors

If Emotiscope's touch sensors are ever misfiring, you can calibrate them to the environment and your fingers with a short on-screen walkthrough.

## Check Firmware Update

The Emotiscope app will check to see if a newer version of the Emotiscope / Remote Control are available. If something new releases, you'll be able to install it automatically with a tap!

## Reset Emotiscope

For when you want to watch how fast Emotiscope reboots.

## Reboot into WiFi Config Mode

This will cause Emotiscope to manually re-open the "Emotiscope Setup" Wi-Fi network so you can change the WiFi network. However, if you changed something about your WiFi network (new password) and Emotiscope can't connect to it anymore, it will automatically enter WiFi config mode. Any time Emotiscope can't connect to WiFi, the indicator lamp on the front will flash.

## MAC

The MAC address of your Emotiscope, in case your WiFi network uses whitelisting.

## Version

The current version of the Emotiscope Engine firmware your device is running.
