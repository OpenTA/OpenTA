
# OpenTA

A reimplementation of Cavedog Entertainment's Total Annihilation (1997).

# Specifications

32-bit conversion from compiled form into a DLL (this project).\
A patched original TotalA 3.1 executable provided with the project.

# Requirements

1) All in-game simulation logic must yield exactly the same results as the original game.
2) All rendering logic and updates must yield the same authentic look of the original game.
3) All data structural updates must yield at minimum the original resulting functionality from the original game.

# The Plan Summarized

1) Convert compiled functions to C++ in project (32-bit) and carefully test each one.
2) Test the resulting 32-bit OpenTA.dll/exe.
3) Convert from 32-bit dll/exe to 64-bit exe.
4) Replace all legacy 32-bit API references with updated 64-bit APIs.
5) Test the resulting 64-bit OpenTA.exe.
