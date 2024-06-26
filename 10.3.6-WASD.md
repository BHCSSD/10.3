# 10.3.6-WASD

Show and tell starter code first, the project is under the starter code. 

```javaScript
function setup() {
  createCanvas(400, 400);
//  x // starting X position
//  y // starting y position
}

function draw() {
  background(220);
  // Draw the block
  rectMode(CENTER);
//  rect(x, y, 50, 50);
  //How do we move the square using grade 1 math?
  


  
  // lets make an if() here
}


function keyPressed() {
// Check for key presses and update the block's position
if (key === 'w') { // W key

}// end W
// if () { // S key

// }
// if () { // A key

// }
// if () { // D key

// }

}// end key pressed
```

## Part 0 - The Setup
make a variable in the gloab variables to hold a value for speed. Just note that `speed` is a sometimes reserved word in different languages,  `let speed = 5` might not work. I usually use `vroom`

Alter the window size to make it 300,300.

## Part 1 - Basic Movement (80%)
1. Draw a small square on the screen (about 20x20).  Alternatively, you can use a small image either way, make instead of hard coding the X and Y, make their values variables 
2. Write code so that it will move using all 4 arrow keys OR you can use A-S-D-W.  
    - Remember:  `keyCode===LEFT_ARROW`
    - Remember:  `key === "w"`

3. Write code so the rectangle wraps the screen when it goes off the edges. 
    - Forget how?  think: if your square is off the window (700) go to the beginning (0)
    - format for if statements
      ```
      if(boolean question){
      your code goes here
      }
      ```
4. Look into how to make the square continuously move instead of a bit at a time. 
5. Optional: If I press space, it should stop.  You can have it stop automatically if you wish.

## Next 10% - Add a power up
1. Create a variable that represents the speed at which the rectangle moves.
2. Then, when you press the `p` key, it should increase this speed.
    -  In other words, from that point on, each time you press an arrow key it should jump further.  You only need to press `p` once and you do not need to hold it down.
    -  You can allow multiple `p` presses to increase the speed each time, OR you can just have one-speed increase that lasts forever.


## Final 10% - Proximity Detection
1. Add a red rectangle that is 40 pixels high and covers the entire top of your screen (the top 40 should be all red).  
2. If your square is touching the red box, in the red box the following text should occur: “Warning: Entering the Enemy territory. Proceed with caution.”

## Tough Challenge - Not for Marks
See if you can find code online to act as a timer.  Five seconds after you press the `p` key, your speed returns to normal.


