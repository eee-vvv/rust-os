# Rust-based Operating System

## About

This project is a work-in-progress. Following the clarifying guide at os.phil-opp.com, I am implementing a free-standing operating system in Rust. After writing the core OS, I plan to build programs that run on the kernel, including:

- A simple text editor
- Games (Minesweeper, Snake)
- ...and more


## Why create an OS from Scratch?

For the past couple of months, I have been learning the Rust language whenever I have the time. Finally, I am at a point where I can embark on a large-scale project that takes advantages of the unique features that Rust has to offer.

By building an OS, I am learning how software functions at the lowest level, and answering the basic question: what does it mean to write a program that relies on nothing but the computer's hardware? As I am a JavaScript programmer, this is great way to learn computer science fundamentals (how exactly does a stack work?, how does software interface with hardware?, etc.), and to become a better Rust developer specifcally and a batter back-end developer overall.

Forced to rely on minimal abstraction, I can't take for granted anything: no keyboard support, no heap, no way to display even text to a display, until I've implemented it by hand.

Follow along to watch me grow and create a fun, little OS!
