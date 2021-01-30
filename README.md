# bfcpu

8-bit CPU design (from scratch) that runs bf. It's still in development.

## About

Ever since I learned about the bf language, it fascinated me that you could code anything in the world with just 8 commands. However, as I learned more about computer architecture and compiler design, I noticed that on modern architecture (where registers can be incremented by factors larger than one and where advanced instructions such as `jmp` are commonplace), the tedious process of incrementing by 1 is... tedious.
My motivation for this project is to create a system architecture that is designed to run bf, and only bf. I don't have any background with computer hardware, electrical engineering, or CPU design, but I am learning as I go. I also don't expect this CPU to be any faster at running bf than a toaster running DOS/V, for 2 reasons:
1) A toaster would probably have a higher clock speed than this CPU
2) The toaster's bf compiler would probably be more optimized than my mess of wiring spaghetti that comprises my CPU
By developing this CPU, I hope to demonstrate that CPUs with alternative, esoteric, or otherwise strange instruction sets are not only possible, but are also interesting.

## Roadmap
	- ~~Finish creating register module for storing important data (current instruction, instruction pointer, etc.)~~
	- ~~Finish creating the RAM module~~
	- ~~Finish creating the instruction module~~
	- ~~Create operation flowchart to dictate order of CPU internal instructions~~
	- Create i/o module
	- Finish wiring of CPU internal instructions and logic
	- Finish wiring of bf instruction logic
