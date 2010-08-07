A very simnple offline mastermind game created for http://js1k.com/
The minified entry version is mini.html
Play at http://mastermind.ekynoxe.com/

Code inspired from the rspec book: http://www.pragprog.com/titles/achbd/the-rspec-book

Tested on OS X 10.5.8 in:
	* Firefox 3.6.2
	* Safari 4.0.5
	* Chrome 5.0.375.125
	* Opera 10.60

RULES:
Guess by submitting with your keyboard numbers from 0-9
After pressing 4 digits the guess is automatically submitted
The result shows symbols:
	* no symbol means no digit is in the code to guess
	* a '-' means one of the digits is in the code to guess, but not at the correct place
	* a '+' means one of the digits is in the code to guess, AND at the correct place
If a digit exists twice in the code to guess, symbols do not represent it, you will have 
to get it by yourself!
An alert is displayed when the code is found, and the game reset
