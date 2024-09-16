# Snort
Snort is a recent project that I worked on and thoroughly enjoyed!

In this project, I developed a CPP DLL that injects into World of Warcraft, overcoming various anti-cheat mechanisms. Once the injection is successful, the internal DLL sets up pipe servers (as demonstrated in my previous project, Pipe-Dreams-R-Us) to facilitate inter-process communication (IPC) with an external GUI process written in C#. The DLL then detours functions within the injected process that are responsible for packet transmission. The arguments and return values of these functions are relayed to the external GUI process via pipes, where they can be edited, dropped, or resent.

Key features of the project include:

Reading and editing packet byte buffers.
Replaying and resending packets.
Crafting and sending custom packets.
The goal of this project was to deepen my understanding of anti-cheat mechanisms and common security practices.


[DEMO VIDEO](https://www.youtube.com/watch?v=j6IGuBMstrg)
