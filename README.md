# Hangmangame
Hangman Game Description
This is a Python implementation of the classic Hangman word-guessing game with a fruit theme. Here's how it works:
Core Functionality:
Word Selection: Randomly chooses a fruit name from a predefined list of 15 fruits (apple, banana, mango, etc.)
Game Setup: Displays blank spaces representing each letter of the chosen word
User Interaction: Prompts players to guess one letter at a time
Progress Tracking: Shows correctly guessed letters in their positions while keeping unguessed letters as blanks
Key Features:
Input Validation: Ensures only single alphabetic characters are accepted
Duplicate Prevention: Tracks previously guessed letters to avoid repetition
Dynamic Difficulty: Gives players (word length + 2) chances to guess
Smart Win Detection: Uses Python's Counter to compare guessed letters with the target word
Error Handling: Gracefully handles invalid inputs and keyboard interruptions
Game Flow:
Display the word as underscores with a fruit hint
Accept letter guesses from the player
Validate input (single letter, not previously guessed)
Update display showing correct letter positions
Continue until word is fully guessed (win) or chances run out (lose)
Technical Implementation:
Uses random.choice() for word selection
Employs collections.Counter for efficient letter frequency comparison
Implements robust exception handling for user input
Features clean console-based interface with real-time feedback

The game provides an engaging command-line experience with educational value, teaching players fruit names while exercising their word-guessing skills.RetryClaude can make mistakes. Please double-check responses.
