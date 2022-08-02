# PWordle
Wordle of dynamic length in Python

### How to run
- It is best to run the code in Jupyter Notebook as the WORDLE grid uses Pandas Dataframe color formating to display letter color
- If you run code in terminal you will not be able to display your guesses

### How to play `PWORDLE`?

0. Set the value for `word_length`
1. **import** * **from** `wordle.py` 
2. Run `play_wordle()` to start a game
3. Code will randomly select an N-letter word from the English dictionary
4. You have **six** tries to guess correctly
5. If you guess the `exact` position of a letter in the word it will turn <span style="color:green">GREEN</span>
6. If you guess a letter, but it is in the wrong position it turns <span style="color:orange">ORANGE</span>
7. If the letter does not exist, it will become `lower` case and remain black ink

## GOOD LUCK AND ENJOY!

#### Example of a single 5 letter game:

<img width="379" alt="Screen Shot 2022-02-12 at 7 16 47 PM" src="https://raw.githubusercontent.com/praveentn/PWordle/main/img1.png">

<img width="785" alt="Screen Shot 2022-02-12 at 7 17 16 PM" src="https://raw.githubusercontent.com/praveentn/PWordle/main/img2.png">

