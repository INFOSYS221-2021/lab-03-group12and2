# Lab 3 Group 12 and 2

Team Members
- Helen Vincent
- Bao Li
- Avneet Sharma

Exercise One: Reversing String
Write the pseudocode instructions for the following:
Given a word or a sentence, display the given word/sentence in reverse order.

START 
GET length of word/sentence
WHILE length of word is greater than zero
	PRINT last letter of sentence/word
	SET length of sentence/word as one less than sentence/word
ENDWHILE
STOP

Exercise Four: Greatest Common Divisor
Write the pseudocode instructions for the following:
Given two integer numbers, find the greatest common divisor. That is, the largest integer that divides both of them with no remainder. You may assume both numbers are positive.

START
GET values for integer1 and integer2
Determine larger value between integer1 and integer2
SET divideflag as true 
SET divider as one 
WHILE divideflag as true 
	SET remainder to result of calculate int1 / divider  (modulo operator) (or calculate remainder) 
	
	IF remainder is NOT INTEGER 
	SET Divideflag as false 
 
	COMPUTE int2 / divider 
	IF remainder is NOT INTEGER
	SET Divideflag as false 
	
INCREMENT divider 
