# Homework #6

## Instructions
---
1. Feynman Writing Prompts - Write out explanations of the following concepts like you are explaining it to a 12 year old.  Doing this will help you quickly discover any holes in your understanding.  Ask your questions on Slack.

	* Functions: 
	Similarly to a variable in algebra, a function captures and stores information. A function is used to capture and store code so that it may be called upon any time it is needed. This reduces redudancy in replicated code. Functions may be hoisted to the top of the code, which means they may be called for use, even when they are not defined until later in the code.  Using is a function is called "calling" the function. Calling, or "using", a function is very similar to the idea of using variables in algebra.  In alegbra, when we use a variable like x, we can substitute whatever information x holds in place of x in an equation. When we call, (or "use"), a function, we can substitute whatever information the function holds in place of the function call. 
	
	* Parameters:
	Parameters are set values that we set aside for use in a function.  They are placeholders for actual values to be plugged in. They are identified at the beginning of the function definition, and then are manipulated in the function itself. It is similar in algebra if we say there are two variables, x and y, and Equation#1 is x + y. X and y both represent values to be plugged in. X and y are the "parameters" of Equation#1. Equation#1 is the "function".
	
	Example:
	function addTwoNumbers(parameter1, parameter2){
	  return parameter1 + parameter2;
	  }
	
	This is similar to alegbra:
	We have two variables: x and y.
	Equation#1 = x + y

	* Arguments:
	Arguments are the actual values we plug in for the parameters.  Arguments are identified when we call the function. If we look at the previous example, Equation#1, which is x+y, is the "function".  X and y are the "parameters".  If we say x is 4 and y is 3, then 4 and 3 are the "arguments" we plug into Equation#1.
	
	Example using above function:
	addTwoNumbers(argument1, argument2);   <--this is the function call with arguments
	
	This plugs argument1 and argument2 into the addTwoNumbers function, which creates: 
	
	return argument1 + argument2;
	
	Similarly in algebra:
	x = 4, y = 3
	Equation#1 = x + y
	Equation#1 = 4 + 3
	
	
	* `if` statements:
	"If" statements are conditional statements which tell us that if some condition is met, then something else happens. For example, if I say, "If it is hot, then we eat ice cream," then the condition that must be met is "It is hot". If that condition is true, then the action that will occur is: "we eat ice cream". If the condition is false, then the action of "eat ice cream" will not occur. An "if" statement works the same way in javascript, except the conditions and subsequent actions are all code.

2. Install Node and NPM.  NPM comes packaged with Node. https://nodejs.org/en/download/

3. Download (clone) this project folder from GitHub.

4. Navigate into the downloaded folder using Terminal(Mac) or Command Prompt(Windows).  `ls`(Mac), `dir`(Windows) and `cd <directory_name>` are the commands you need to navigate around.

5. Once you are in the folder type the command `npm install`.  This will fetch all of the needed requirements for the project.

6. Run `npm test` to run the automated tests.  At first all of the tests will be broken.  You will fill out the functions in `exercises.js` to make the tests pass.


#### Congratulations on finishing Homework #1!
Apply to our full-time or part-time immersive program to learn cutting edge technologies that are used by top technology companies around the world.

Our part-time and full-time courses are 13 intense weeks of focused study on the most relevant technologies.  

Class sizes are small to ensure that each student gets individual attention from our world class instructors to help them succeed.  We also provide career support both during and after the course to help you succeed.  We are committed to your success.

For more information visit: https://www.lambdaschool.com
