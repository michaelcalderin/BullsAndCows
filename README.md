# Bulls and Cows

## Important Links
- Link to Demo: https://youtu.be/SYhDWq9fQeQ
- Link to Formal Presentation: https://youtu.be/_9VsliHPJjo

## Overview
Bulls and Cows is a simple game with a secret 4-digit password unknown to the player. The player will input guesses to try to crack the code. However, a code cannot have repeating digits. Bulls are the digits in the guess that are in the correct spot. Cows are the digits in the guess that are not in the correct spot but do appear in the password. Entropy represents how close you are to cracking the code. Entropy is the uncertainty of a code being the password so lower uncertainty is better, and 0 entropy would be a correct guess of the password. Note that the unit for entropy is bits but it is not displayed in the game for the sake of being user friendly. This was implemented in Python with one script titled “BullsAndCows.py".

## Documentation
Refer to documentation in zip folder for more information. The formal presentation link will explain the theoretical framework behind information theory and specifics on how entropy was calculated for this project. The demo will explain the code and demonstrate the game in action.
