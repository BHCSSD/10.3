# 10.3.4-Coolness-quiz

## **1.5-2 classes at most for this assignment**

Everyone knows that your teacher is the epitome of "cool" and that you all aspire to be like him.  However, not everyone can be.  Therefore, your goal is to create a 5 question test to determine how cool your user actually is.  You will store a score variable that increases based on the user’s answers. At the end, you will give them a coolness rating. 


## Part 0 - The Setup (20%)
**Save the file with the correct name**
1. Create a `score` variable in the global variables area and set it equal to zero.
2. Create a `name` variable in the global variables area.
3. In the `SETUP()` function, use `window.prompt()` to ask the user their name.
    - You are then to use this name variable somewhere in the rest of the program.
    - This is the only time you will use `window.prompt()` for this assignment.
    - Make sure to **NOT** use `window.prompt()` in draw. I know you want to, but woe is the student who does.


## Part 1 - Draw & KeyPressed Functions (60%)
### Draw Function (20%)
1. Use `TEXT()` lines to add a title to your Coolness Test.
2. Use `TEXT()` lines to ask the user 5 multiple-choice questions, using the following instructions.
3. All 5 questions are going to appear on the screen at all times.
4. Give 3 choices for each question. Each question will tell the user to choose from a different set of keys as follows:
    - Question 1 will use a, b & c.
    - Question 2 will use d, e & f, etc.

```javaScript
//Example:
Question 4:  Which of the following is the best movie series?
i)  Starwars	j) Marvel Universe	k) Hunger Games
``` 
	
5. In the draw function, show the user’s name and the value of the SCORE variable at all times somewhere near the bottom of your screen.

   
```javaScript
"Petra, your coolness score is currently:  4"
```

### KeyPressed Function (40%)
1. Create a long chain of  IF...ELSE IF… ELSE IF statements that check for the keypresses.
    - As your user will only ever press one key at at time, all the keys (except the first one) will be in ELSE IF statements.  

## Part 2 - Pretty Up Your Test (Next 10%)
1. Add at least one image and at least one font to your program.
2. Change your text sizes to make it look pretty and to make your score stand out.
3. Add icons/ images to each question
4. Make sure your code is neat
    - indentation
    - //comments
      - end of the }
      - any major code block
    - proper spacing between code blocks. Think of this like paragraphs in LA class 


## Part 3 - Give them a Rating (Final 10%)

1. Add a text line below your score that says something such as “Press the ? key to test your score.”

2. Add one more `ELSE IF`  statement to your keypress function that looks for the question mark.
3. Create a 3-part rating system (Diamond, Silver, Coal? ) and based on their score, give them a rating.
    - In other words, if they get more than X points, you tell them they get a DIAMOND coolness rating.  If they get less than Y points, you give them a SILVER coolness rating.  ELSE they get a COAL coolness rating
    - Half marks if the scale/rating is on the screen at all times, full marks if it only shows up when I press ?

4. Optional, add another keypress that resets the score back to zero and lets them take the test again. Not for marks.


```javaScript
// Oh scary.... no starter code. You can use your in-class examples for help. 
function preload(){
}

function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(220);
}

function keyPressed(){
}
```

