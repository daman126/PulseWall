# PulseWall
PulseWall is a wall-mounted, interactive e-ink display that keeps your day organized and inspired. It cycles through multiple screens with the turn of a knob
PulseWall

PulseWall is a wall-mounted, low-power e-ink display that shows useful daily information at a glance. It is designed to be always-on, distraction-free, and controlled using simple physical knobs instead of a touchscreen.

The display cycles between multiple screens, including the current time and date, weather, calendar events, and motivational quotes. Interaction is handled entirely through rotary knobs, making the interface intuitive and tactile.

Features

E-ink display for low power usage and high readability

Multiple screens:

Home (time and date)

Weather

Daily calendar events

Motivational quote

Rotary knob to switch between screens

Secondary knob to scroll content (events or quotes)

Automatic return to the home screen after inactivity

Wall-mounted enclosure with a slim profile

Designed to run continuously

Planned Hardware

Raspberry Pi Pico W

Small SPI e-ink display

Two rotary encoders with push buttons

Rechargeable battery (with charging module)

Custom wall-mounted case

Software Overview

PulseWall runs on MicroPython and uses a simple screen state system.

Each screen has its own draw function

Knob input updates the active screen or scrolls content

A timer tracks inactivity and returns to the home screen

Data such as weather and calendar events are fetched and cached to reduce power usage

This repository currently contains skeleton code and design files used for planning and review before hardware is purchased.

Repository Structure
PulseWall/
├── firmware/      # MicroPython control logic and screen system
├── case/          # Case design files and notes
├── docs/          # Diagrams, sketches, and documentation
└── README.md

Project Status

This project is in the blueprint and design phase.
All code and models are preliminary and are intended to demonstrate the system design prior to applying for hardware funding.
