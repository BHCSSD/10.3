# 10.3.2-Music comp


You will need a simple logo for a music contest, you can use mine, or quickly go find one. 



```javaScript
//Global Variables 
let name;
let year;
let age;
let instrument;
let cat;
let logo;
let angle = 0;

function preload() {
    // LOADS IMAGE for logo here  remember to use createImg()... and hide it after... im sorry I know it sucks
}//end preloading of images and fonts

function setup() {
  createCanvas(600, 500);
  background(155, 135, 155);
   
  textSize(24);
  text("Click anywhere to register for the competition.", 50, 400);
}//end setup

function draw() {
    angleMode(DEGREES); // js thinks in radians... BOO so we use this to translate it to degrees
    translate(300,150); // moves x,y 00 to where ever we want...
    rotate(angle);
    
    angle++;
    if(angle>360){
        angle = 0;
    }//end of if

    imageMode(CENTER);
    image(logo, 0,0);
    translate(0,0); // translate back to real 0,0

}//end draw



function mousePressed() {
    background(155, 135, 155);
    // ask for users name here in the name variable
    // print("Debug: testing name variable: " + name);
    // ask the user their birth year in  the year variable
    //age // do the math to figure out how old our user is

    fill(0);
    noStroke();
    textSize(24);
  
//    text("Competitor Name: " , 50, 300); // joing the text with the `name` variable
//    text("Age: " , 50, 325); // joing the text with the `age` variable 

//    if () { // old ones... over 21
//        text("Division: Senior", 50, 350);
//    } else if () { // juniour ones... 16 and up
//        text("Division: Junior", 50, 350);
//    } else {  // this is our catch-all,  notice it doesn't what a conditional statement () it just is
//        text("Division: Child", 50, 350);
//    }

// ask the user  what category they want, fill in the `cat` variable    ("What category pro or amateur?");
//        if( ){ //check to see if they are "pro"
//        text("Fee for Professionals: $100", 50, 400);
//    } else { // if they are pro that means they are ...
//        text("Fee for Amateurs: $30", 50, 400);
//}


}//end mousePressed
```
