# APK Mobile Project

This project was part of a riddle-based assignment given by our teacher.  
We were provided with an APK file and some source code, and our task was to analyze and solve the puzzle behind it.

## How to Play – Quick Guide

There is an internal list of U.S. states:
California, Texas, Florida, New York, Illinois, Pennsylvania, Ohio, Washington, Michigan, Arizona

Each state corresponds to a digit from 0 to 9, in the given order.

Arrow directions are also mapped to numbers:

- **Left arrow** → `0`
- **Right arrow** → `1`
- **Up arrow** → `2`
- **Down arrow** → `3`  


### Solving the Puzzle

1. Start with an ID number.
2. Identify the **8th digit** of the ID — this determines which state is selected from the list above.
3. Go through each digit in the ID number:
    - Perform a modulo operation: `digit % 4`
    - Based on the result, press the corresponding arrow direction as listed above.


## Screenshots
<img src="screenshots/game" alt="game" width="270"/>
<img src="screenshots/result" alt="results" width="270"/>

---
