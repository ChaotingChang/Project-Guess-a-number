<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Guess A Number
*Chao-Ting Chang*

*Data Analytics June 19, Barcelona & 26/06/2019*

## Content
- [Project Description](#project-description)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

<a name="project-description"></a>

## Project Description
This project aims to build a small game called "Guess A Number". There are three levels, the first one is only to guess a number between 1 and 10. The second level is to guess between 1 and 50, but the computer will give you a hint. The last level is to guess a four-digitals number, where computer will tell you how many match and mis-match you have as a hint.



<a name="workflow"></a>

## Workflow
Here is how I developed my project.
1. Create a gitignore file. (I don't want to provoke Eva. ;D)
2. Playing Process:
    a. Computer generate a number
    b. Ask user to guess a number
    c. Compare the result and give a hint.
    
3. What I need for the playing process:
    a. The range of the number to be guessed.
    b. Make the computer generate a number lays in between the range
    c. Define ow many time one is allowed to guess
    d. Ask the user to guess a number (Think: what if the user give a number out of range? What if the user give a letter?)
    e. Compare the result and give a hint to user.
    
4. In response to to the step 3:
    a. Create two variables to establish the max and min values
    b. Use the max and min values and random function to generate a random number and save it as a variable
    c. Create a variables to establish how many time the player can guess
    d. Create a function where allow user to input a number which lays inside our rule
    e. Create a function to compare the result, use the 4c to restrict the playing time
    

<a name="organization"></a>

## Organization


<a name="links"></a>

## Links

[Repository](https://github.com/ChaotingChang/Project-Week-1-Build-Your-Own-Game.git)  
[Slides](https://slides.com/changchao-ting/guess-a-number/live)  
[Trello](https://trello.com/invite/b/bshhoev1/6c8fb35007af95fce2898be526d1c7d6/guess-a-number)  
