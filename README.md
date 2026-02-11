PulseWall

PulseWall is a wall-mounted, always-on e-ink display designed to show useful daily information in a calm, distraction-free way. Instead of using a touchscreen or phone app, PulseWall is controlled using physical rotary knobs, making interaction simple and intentional.

The display cycles between multiple screens including the current time and date, weather, calendar events for the day, and a motivational quote. After a period of inactivity, the device automatically returns to the main screen.

Features

Wall-mounted e-ink display

Multiple screens:

Home screen (time and date)

Weather screen

Daily calendar screen

Motivational quote screen

Rotary knob to switch between screens

Secondary knob to scroll content (events or quotes)

Automatic return to the home screen after inactivity

Always-on operation using wall power

Planned Hardware

Raspberry Pi Pico W

Small SPI e-ink display

Two rotary encoders with push buttons

USB wall power adapter

Custom wall-mounted enclosure

Software Overview

PulseWall runs on MicroPython using a simple screen-state system.

Each screen has its own draw function

Knob input updates the active screen or scrolls content

An inactivity timer automatically returns the display to the home screen

Weather and calendar data are fetched periodically and cached to avoid unnecessary updates

This repository currently contains planning-phase code and design files used to demonstrate system design prior to hardware purchase.

Power

PulseWall is powered via a USB wall adapter and is designed to run continuously.
An e-ink display is used for its readability and ability to retain images without constant power or refreshes.

Repository Structure
PulseWall/
├── firmware/      # MicroPython screen and input logic
├── case/          # Case design files and notes
├── docs/          # Diagrams and system documentation
└── README.md

Project Status<img width="626" height="463" alt="Screenshot 2026-01-16 184551" src="https://github.com/user-attachments/assets/53cb5c0c-e28e-485d-b4bf-f51365a9ae97" />


This project is currently in the blueprint and design phase.
All code and models are intended to demonstrate the planned system before applying for hardware funding.


