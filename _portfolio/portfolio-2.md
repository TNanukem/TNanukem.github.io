---
title: "Chip-8 Emulator"
excerpt: "An Chip-8 emulator developed in C++<br/><img src='/images/space_invaders_chip8.png'>"
collection: portfolio
---
# Chip-8 Emulator

![Space Invaders Running on the Emulator](https://github.com/TNanukem/tnanukem.github.io/blob/master/images/space_invaders_chip8.png "Space Invaders Running on the Emulator")
![Pong Running on the Emulator](https://github.com/TNanukem/tnanukem.github.io/blob/master/images/pong_chip8.png "Pong Running on the Emulator")

## About the project
This was my first approach in emulator development and I'm really proud of how it turned out. However, there are sensbile modifcations that can be made in order to improve the project as a whole.

The use of SDL may not have been the best choice, since it doesn't allow, natively, for the development of the UI, so, in order to make it will be necessary to use another library and try to integrate both of them. In my next emulations projects I probably would look forward to using another tool.

Also, the timing of this emulator is poorly implemented. The sound has bugs because the timers doesn't reduce at the expected frequency of 60 Hz, also, the emulator can't maintain a stable frame rate. For my next projects, with more complex systems, this will be a major worry.

Finally, some aspects about the architecture used still worry me. I didn't really used a well object-oriented structure because of my C development backgound. This is another major focus that should be addressed on future projects.

## About Chip-8
Chip8 was basically a virtual machine developed in the 70s that allowed games to be written in its language and then easily interpreted. Several classical games can be played on a Chip8 machine, like Pong and Space Invaders.

You can find more information about the project on [GitHub](https://github.com/TNanukem/chip8-emulator/)
