# 10.3.5-Guess-a-number

```javaScript
let compnum  = 20
let usernum = -1; // why is the user number set to -1 right away? 

function setup(){
  let compnum= floor(random(0,101));//pick a number between 0 and 100. 
  
  
  usernum = window.prompt("pick  number between 1 and 100");  // this 1*window.prompt is a unique thing... 

  while(compnum!=usernum){ // while the comps number is not equal to your guess
    if(){ // fill out the () to see if usernum is less than compnum
      usernum = 1*window.prompt("guess higher");
    } //if 
    else{
      usernum = 1*window.prompt("guess lower");
      }//else
    }// end of while 
    window.alert("You win. the number was " + usernum)  // the + unsenum here combines the string "" with the number  in usernum
}//end setup

```
