# Auracle

> A music device that uses oracle cards to choose your song of the day.

![Auracle cover image](images/cover.jpg)
<!-- Upload a picture called cover.jpg to the images folder and it will appear here. -->

**Course:** [Tangible User Interfaces 2025/26](https://www.ciid.dk/idp-courses/tangible-user-interface-2025-26), Interaction Design Programme, Copenhagen Institute of Interaction Design (CIID)
**Video:** [Watch on Vimeo](https://vimeo.com/1176640904)
**Project page:** [Auracle on ciid.dk](https://www.ciid.dk/idp-projects/auracle)

## Team

- Diana Chaves
- Haley Rowland
- Cassandra Quesada

## About the project

Auracle is a music player that mixes the idea of a cassette player with oracle cards. Each card stands for a meaning, like freedom, inner power or release. You pick a card by intuition, place it in the cassette compartment, and Auracle asks you a question related to that card. An LLM interprets your answer, how you feel and what you need, and picks a song of the day for you.

One of the biggest lessons for the team was how much detail and iteration it takes to make a tangible interface feel simple.

## How it works

1. The user picks an oracle card from the deck.
2. The card goes into the cassette compartment and is recognised with NFC.
3. Auracle asks the user a question related to the meaning of the card.
4. An LLM interprets the answer and the user's state of mind.
5. Auracle chooses and plays a song of the day.

## Hardware and services

- Arduino Uno Q
- NFC reader and NFC tagged oracle cards
- Sensors to read the user's physical actions
- Speaker
- LLM API

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

This project is the intellectual property of its authors: **Diana Chaves, Haley Rowland and Cassandra Quesada**.

It is shared under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license. You are free to use, adapt and share it, also commercially, as long as you **credit the authors**. You can use this text:

> *Auracle* by Diana Chaves, Haley Rowland and Cassandra Quesada. Created for the Tangible User Interfaces course 2025/26 at the Copenhagen Institute of Interaction Design (CIID). Licensed under CC BY 4.0. https://www.ciid.dk/idp-projects/auracle
