# Curio

> A handheld device with magnetic lenses that helps children explore the world with AI.

![Curio cover image](images/cover.jpg)
<!-- Upload a picture called cover.jpg to the images folder and it will appear here. -->

**Course:** [Tangible User Interfaces 2025/26](https://www.ciid.dk/idp-courses/tangible-user-interface-2025-26), Interaction Design Programme, Copenhagen Institute of Interaction Design (CIID)
**Video:** [Watch on Vimeo](https://vimeo.com/1176196472)
**Project page:** [Curio on ciid.dk](https://www.ciid.dk/idp-projects/curio)

## Team

- Davide Airoldi
- Pedro Josué Matarrita Brenes
- Andrés Gómez
- Kabir Shrivastava

## About the project

Curio gives children a way to explore and learn about the world around them with the help of AI, without a smartphone or a chatbot. The child points Curio at something, presses a button, and hears a short, child friendly explanation about it.

The key element is a set of interchangeable magnetic lenses. Each lens is a different point of view (for example, the orange History lens), and it changes the instructions sent to the AI together with the photo. Swapping a lens is the physical way of changing the prompt. Three lenses were made for the prototype, and the team built five prototypes before reaching the final version.

## How it works

1. The user attaches a lens. The device detects which lens it is through a magnetic recognition system.
2. The user points the camera at an object and presses the button.
3. The photo is sent to the AI together with instructions that depend on the lens.
4. The answer is read out loud through the speaker in simple language.

## Hardware and services

- Arduino Uno Q
- HD camera
- Amplified speaker
- Physical button
- Magnetic lenses and lens detection system (three lenses)
- AI API

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

This project is the intellectual property of its authors: **Davide Airoldi, Pedro Josué Matarrita Brenes, Andrés Gómez and Kabir Shrivastava**.

It is shared under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license. You are free to use, adapt and share it, also commercially, as long as you **credit the authors**. You can use this text:

> *Curio* by Davide Airoldi, Pedro Josué Matarrita Brenes, Andrés Gómez and Kabir Shrivastava. Created for the Tangible User Interfaces course 2025/26 at the Copenhagen Institute of Interaction Design (CIID). Licensed under CC BY 4.0. https://www.ciid.dk/idp-projects/curio
