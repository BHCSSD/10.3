# 10.3.3-Drivers-test

## Todo: 

Please do items 1-4 on your own. I will go through the next part with you. 
1. Load a logo for a driver's school
2. Add variables for age and test score
3. use window prompt to ask users for their age **DO NOT USE WINDOW PROMT IN `DRAW()`**
4. if their age is 16, they can do the test, else if above 14 learners... else .... hit the road jack.
5. Put in the test answers
    - use `key === '3'` to check if the last key they pressed was "3"  Remember the "" for all of these

```javaScript
// Drivers Test
//Global Variables
let logo;
//2)
//

function preload(){
  // logo = createImg("");
}//end preloading of images and fonts

function setup() {
  createCanvas(600, 400);
  background(100,92,80);
// 3) 

}//end setup
function draw() {
    background(255,0,0);
    image(logo, 50,50,100,100);

    textSize(18);
    fill(255, 255, 0);

  // 4) Logic for if statements 
    // if(){
    //     text("You are eligible for your full license." , 50, 200,);
    // } else if (){
    //     text("You are eligible for your Learner's license." , 50, 200,);
    // } else {
    //     text("You are not eligible. Beat it loser.", 50, 200);
    // }// end 

 
    text("Your current score: " + testScore, 200, 380);
    text("How many colors are there on a traffic light?", 50, 250);
    text("Which color is in the middle of a traffic light? (type r, g or y)", 50, 275);
    text("On what side of the road do they drive in Australia? (use the arrow keys)", 50, 300);
    text("Are kangaroos eligible for driver tests? (type m for yes, or n for no)", 50, 325);

}//end draw

function keyPressed() {
  //5) answering the questions
   // if(){
    //    testScore++;
    //} else if (){ // set to y
    //    testScore++;       
    //} else if (){ // set to left arrow...  this is something new look up keyCode in p5 reference
    //    testScore++;
    //} else if(){ // set to n
    //    testScore++;
   // }
 
}//end keyPressed
```
