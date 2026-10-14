# Sketch Tales

> A bedside storytelling lamp that turns a child's drawing into a narrated bedtime story.

![Sketch Tales cover image](images/cover.jpg)
<!-- Upload a picture called cover.jpg to the images folder and it will appear here. -->

**Course:** [Tangible User Interfaces 2025/26](https://www.ciid.dk/idp-courses/tangible-user-interface-2025-26), Interaction Design Programme, Copenhagen Institute of Interaction Design (CIID)
**Video:** [Watch on Vimeo](https://vimeo.com/1176503674)
**Project page:** [Sketch Tales on ciid.dk](https://www.ciid.dk/idp-projects/sketch-tales)

## Team

- Prianka Kaur
- Naman Jain
- Nikhil Sajjan
- Hitesh Kukreja

## About the project

Sketch Tales is a bedside lamp for children aged 7 to 10. A child places a hand drawn sketch on the lamp's platform and the lamp tells a bedtime story inspired by that drawing. While the story is narrated out loud, the LEDs in the lamp change to match the mood of the story, so a simple drawing becomes a story with sound and light.

The idea is that children take part in creating the story instead of only listening to one, making bedtime more personal and imaginative.

## How it works

1. The child places a drawing on the platform of the lamp.
2. The Arduino manages the interaction and sends the image to a cloud server.
3. AI models (Claude and OpenAI) read the drawing, describe it and write a story from it.
4. The story text is turned into speech with ElevenLabs.
5. The lamp plays the story through its speaker while the LEDs react to the narration.

## Hardware and services

- Arduino Uno Q (Linux based board, programmed in C++ and Python)
- Camera to capture the drawing
- Speaker
- LEDs
- Cloud server
- APIs: Claude, OpenAI, ElevenLabs

<!-- Team: please check this list and complete it with the exact components and libraries you used. -->

## What is in this folder

| Folder | What you will find |
|---|---|
| [`code/`](code/) | Source code (Arduino, Python, server) |
| [`schematics/`](schematics/) | Wiring diagrams, bill of materials, fabrication files |
| [`images/`](images/) | Photos of the prototype and the process |
| [`presentation/`](presentation/) | Final presentation and other documents |

## How to build it

<!-- Team: write the steps someone would need to follow to make this project work.
     For example:
     1. Build the circuit following schematics/...
     2. Install these libraries: ...
     3. Copy code/secrets.example.h to code/secrets.h and add your API keys
     4. Upload code/arduino/... to the board
     5. ... -->

*Coming soon.*

## License and credits

This project is the intellectual property of its authors: **Prianka Kaur, Naman Jain, Nikhil Sajjan and Hitesh Kukreja**.

It is shared under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license. You are free to use, adapt and share it, also commercially, as long as you **credit the authors**. You can use this text:

> *Sketch Tales* by Prianka Kaur, Naman Jain, Nikhil Sajjan and Hitesh Kukreja. Created for the Tangible User Interfaces course 2025/26 at the Copenhagen Institute of Interaction Design (CIID). Licensed under CC BY 4.0. https://www.ciid.dk/idp-projects/sketch-tales
