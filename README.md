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
	SET commondivisor to zero
	DETERMINE smaller value between integer1 and integer2
	SET smaller integer as smallestinteger
	FOR every number from 1 to smallestinteger
		IF integer1 and integer2 is divisible by the number with no remainder
			SET commondivisor to number
		ENDIF
	STOP
