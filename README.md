**1. Description**

A Python console game where the player tries to guess a randomly chosen number between 1 and 100. The difficulty can be set to "easy" or "hard", affecting the number of allowed guesses. After each guess, the program tells the player if their guess is too high or too low and deducts an attempt. The game ends when the correct number is guessed or the player runs out of attempts.

**2. How It Works**

1. The game starts by displaying a logo and introducing the rules.

2. The program selects a secret number between 1 and 100.

3. Players choose a difficulty: "easy" (10 attempts) or "hard" (5 attempts).

4. The player repeatedly guesses the number; the program provides high/low feedback.

5. Attempts are tracked and deducted with each wrong guess.

6. The player wins by guessing correctly or loses if attempts run out.
   

**Operators and Functions Used**

**Operators:**

= (Assignment): Assigns values to variables and updates attempts.

> and < (Comparison): Compares the guess to the answer for feedback.

== (Equality): Checks if the guess matches the answer and turns are depleted.

- (Subtraction): Deducts an attempt for an incorrect guess.

: (Colon): Structures blocks for functions, loops, and conditional statements.

**Functions and Methods:**

print(): Displays instructions, feedback, and results.

input(): Collects user inputs for guessing and difficulty level.

int(): Converts string user input into an integer for guess comparison.

randint(): Randomly selects a secret number between 1 and 100.

**User-defined functions:**

check_answer(): Evaluates the guess, gives feedback, and returns remaining attempts.

set_difficulty(): Prompts for difficulty selection and returns the appropriate number of turns.

game(): Main function orchestrating the game flow.

while loop: Keeps prompting guesses until win or loss.
