WARNING, PLEASE OPEN THIS FILE IN THE GITHUB EDITOR OR ANOTHER RESPECTIVE IDE TO SHOW INDENTATION

Stanley Parable: Ultra Deluxe vs Firewatch

Stanley Parable: Ultra Deluxe: Component feature: Narator
	The first choice that the player has to make is to go through either the left or right door, 
	the narrator also tells the player to go through the left door, 
	
Firewatch: Component feature: Tough choices
	

Optional Tutorial (Not included in word count):
How to:
  Dialogue System:
	The Dialogue system can be used with the understanding of a few keys.
	To make a character say something, put a "-" before the character name then 
	indent everything you want the character to say like this:
	  -Cameron
	  	I am Cameron
	  	I like to eat
	To make a character ask a question you need to put a "?" at the end of the line that will ask the question,
	then indent all the options you want the player to have access to like this:
	-Cameron
	  	What would you like to eat?
		 Soup
		 Pasta
		 Pizza
	You can also expand on this by adding new paths indented after a selected option like this:
	-Cameron
	  	What would you like to eat?
		 Soup
		   -Friend
			 Yeah that sounds good
		 Pasta
		   -Friend
			 Hm I don't really like pasta
		 Pizza
		   -Friend
			 No comment
