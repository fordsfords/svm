# svm
Simple (Stupid) Virtual Machine

As part of my personal hobby of writing software,
I want to create a hypothetical instruction set and write an emulator for it.

Eventually I'll write a macro assembler and a simple (stupid) OS for it.

And, of course, write a simple (stupid) adventure game to play on my emulated 
simple (stupid) machine running a simple (stupid) OS.

## Why Stupid

So, you might be wondering, why (Stupid)?
I got a BS degree in Computer Engineering in 1980.
I studied hardware, but not sophisticated CPU design topics.
Most of my knowledge and understanding of low-level CPU design comes from
playing with a 6800-based single-board computer.
And that was 42 years ago, so my memory of it is VERY hazy.

If I wanted a non-stupid machine,
I would stop what I'm doing and embark on a journey of study
to re-learn what I've forgotten and learn what I never knew,
so that my CPU design would be potentially useful, possibly practical,
and maybe even interesting to others.

I'm not going to do that.

Remember, this is my hobby.
And like most hobbies, usefulness, practicality,
and interest to others are not goals.
A hobby's primary goal is to occupy the hobbiest in a pleasurable way.
For me, I get a lot of pleasure out of inventing wheels,
even though those wheels have already been invented, refined,
and discarded for better wheels.

Wish me luck.


## Machine Description

I guess I need to give it a number.
All CPUs have a number.
This is for the S-10559 (the 'S' is for simple (stupid)).
I think there is one other human on the planet who knows where that
number comes from, and he's not likely to be interested in this project.

Although I have distant plans to implemnt virtual memory,
I'll start out with a M6800-style architecture without user/kernel modes.

Here's some CPU specs:

* Address bus: 64-bits.
* Data bus: 64-bits.
* ALU: 64-bit 2s compliment, integer only.
* Registers: 256 (some of them special-purpose).
* I/O: memory-mapped.
* Caches: none.
* Interrupts: TBD

## Instruction Encoding

I want to be reasonably memory-efficient.


## License

I want there to be NO barriers to using this code, so I am releasing it to the public domain.  But "public domain" does not have an internationally agreed upon definition, so I use CC0:

Copyright 2020 Steven Ford http://geeky-boy.com and licensed
"public domain" style under
[CC0](http://creativecommons.org/publicdomain/zero/1.0/):
![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png "CC0")

To the extent possible under law, the contributors to this project have
waived all copyright and related or neighboring rights to this work.
In other words, you can use this code for any purpose without any
restrictions.  This work is published from: United States.  The project home
is https://github.com/fordsfords/svm

To contact me, Steve Ford, project owner, you can find my email address
at http://geeky-boy.com.  Can't see it?  Keep looking.
