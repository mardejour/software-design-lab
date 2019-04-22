# MARYAM's Technical Journal

## Week Two (1/30 to 2/6)

This week, I spent part of my time reviewing Git and the command line, including an hour with the DHRI command line tutorial. I found Git to be tough going, but feel like I made solid progress learning how to use pipes on the command line, though I'm still a little confused on the details of how they work. I also started learning how to run scripts in Python, which was very time consuming.

Hour 1: Git review using Pro Git book
Hour 2: Git review using Pro Git book
Hour 3: Phone call with classmate to fiture out pipes
Hour 4: Tried running a "hello world" Python script
Hour 5: ''
Hour 6: ''
Hour 7: Should have given up, but got the script eworking, though I'm still not sure what went wrong.

## Week Six (03/07)
After introducing myself to programming paradigms, I wanted to learn to create and use functions in Python. Out of all three paradigms, I found functional concepts to be the easiest to grasp compared to others, because instead of writing a new code it allows us to reuse a piece of code by changing different values and reuse it multiple times for different purposes.

Hour 1: I learned to define a function and assign a procedure for it to call a function using parameters and arguments. 
In addition, I practiced if, elif, and else statements and tried to import a function into python. 
In the course of doing this I discovered several new operators, such as:
*= 
**
f ....
tbc
I also learned more about built in functions in Python. 
Hour 2: I reviewed DHRI's HTML and CSS tutorials to refresh my memory 
Hour 3: Classes and Instances - learned to create methods wwithin a class (__init___)


Week Seven (03/21)
this week i learned more expressions and what they mean:

+= to sum and reassign (or incriment?) 


operators: if statement (true/false), don't forget curly brackets around the line of code to run;
else & else if clauses (I wasn't sure if it will only run if the previous statement was false, note that only one of them will run, never both);
logical operators: && - logical 'and' operator, will return true if placed between two ooleans that are both true; for example, if it's the weekend and it's sunny out, we are going to have a picnic . if one them is false, there won't be no picnic.

if (True && False) == False 
logical "or" operator || - will retunr true if placed between two booleans and either is true.

03/31 JS Practice 

This Sunday I wanted to work with Java Script (or ECMAScript?). While it wasn't covered in our lab, it bears many similarities to other PLs. For my practice today I will be referring to Fullstack Academy's practice sets, but will be adding my own definitions and names to arguments. 

#1 Define a function 'Aquafina' that accepts an optional string argument called 'quality'. 'Aquafina' should return quality attributes if 'quality' is present. 

const 'Aquafina' = 'quality' => {
   if(typeof quality === 'string' && quality.length > 0) {
     return 'Pure water'  + '!';
    }
    
    return (" "); 
  }
 
this works, but can be improved by adding template literals(``). So I modify line 61. 
    
const 'Aquafina' = 'quality' => {
   if(typeof quality === 'string' && quality.length > 0) {
     return 'Pure water'${quality!};
    }
    
    return (" "); 
  }

another way to shorten this is: 

const 'Aquafina' = 'quality' => {
   if(quality) {
     return 'Pure water'${quality!};
    }
    
    return (" "); 
  }
* a truthy value is a value that is considered true when encountered in a Boolean context. 

another way they suggest is using a ternary operator: 

const 'Aquafina' = 'quality' => {
//if some condition ? true return : false return
   if(quality) {
     return quality? `Pure Water $(quality!)`: " ";
    }
    
question: do i need to define what to return if 'otherwise' happens? like blank space? 

#2. Do you play tetris? 
define a function `do you play tetris` that accepts a string as an argument. 
`do you play tetris` should retrn true if the inputted string starts with the letters 's' or 'S', otherwise `do you play tetris` should return false. 

const doyouplaytetris = (aStr) => {
 if(aStr[0] === 's' || (aStr[0] === 'S';) {
   return true; 
  }
  
  return false: 
  
  }
  
the key here is using Braket Notation. when we use the []  to access an index or key value of a string, array or object. here i used it to access the 0 index which is where the first letter of he string is. 

#3. Last Character

Define a function 'LastCharacter' that accepts two strings as arguments. It should return true if both strings end wwith the same character, otherwise it should return false.

//off by one errors 
const LastCharacter = (strOne, strTwo) => {
  if (strOne[strOne.length - 1] === strTwo[strTwo.length - 1]) }
     return true; 
     }
     
       return false; 
   }

#4. Max of Three 

Write a function that accepts three number args, 'MaxofThree'should return largest number of the three. 

const (maxOfThree) = (NumOne, numTwo, numThree) => {
  if(numOne > numTwo &&  numOne > numThree) return numOne;
  if (numTwo > numOne && numTwo > numThree) return numTwo; 
  if numThree > numOne && numThree > numTwo) return numThree; 
  }

#5. Every which way

Write a function 'everyWhichWay' that accepts three number arguments. It should:
- return 'sum' if the sum of the the first two numbers equals the third; 
- return 'difference' if the first number minus the second equals the third;
- return 'product' if the product of the first two numbers equals the third; 
- return 'null' if none of the above are true; 

const everyWhichWay = (numOne, numTwo, result) => {
  if (numOne + numTwo === result) return 'sum'; 
  if (numOne - numTwo === result) return 'difference'; 
  if (numOne * numTwo === result) return 'product';
  if (numOne / numTwo === result) return 'fraction'; 
  return null; 
} 
 
April 21

Learn Python the Hard Way: 27-34

For this week’s journal I’m going to learn about Boolean logic expressions. Zed compares them to scales in music, so I’m really, ahem, “excited” to find out if they are akin. I remember having a really hard time practicing scales, especially remembering finger placements and working up the speed. I had countless nightmares about coming to class underprepared and having to face another “whiplash moment” from my old Soviet teacher, who placed unreasonable demands on her students, by today’s standards anyway. Suffice it to say I wasn’t one of her brightest students. I mean statements like squeeze the sound like a lemon didn't mean much for a 14 year old, but looking back at it now I guess I could have tried to be more soulful. Thankfully, that is not a requirement in programming *PHEW*!

I've taken some time to memorize these logic problems and ow I'm going to type each problem in once again: 

True and True - True 
False and True - False 
1 == 1 and 2 == 1 - False 
"test" == "test" - True
1 == 1 or 2 != 1  - True 
True and 1 == 1 - True
Fase and 0 != 0 - False
True or 1 == 1 - True
"test" == "testing" - False
1 ! = 0 and 2 == 1 - False 
"test" != "testing" - True
1 != 0 and 2 == 1 - False 
"test" != "testing" - True
"test" == 1 - False 
not (True and False) - False 
not (1 == 1 and 0 != 1) - False 
not (10 == 1 or 1000 == 1000) - False 
not (1 != 10 or 3 == 4) - False 
not ("testing" == "testing" and "Maryam" == "So Soulful") - True 
1 == 1 and (not ("testing" == 1 or 1 == 0)) - True 
"sound" == "lemon" and (not (3 == 4 or 3 == 3)) False 
3 == 3 and (not ("testing" == "testing" or "Python" == "Hard")) False 







