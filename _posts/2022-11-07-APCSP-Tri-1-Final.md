---
toc: true
layout: post
description: My blog of the Trimester 1 Final
categories: [markdown, week Final]
title: Trimester 1 APCSP Final
---

## I got a 41/50 on the final, and these are the questions I got wrong.

### Question 50

Consider the following procedures for string manipulation.

Procedure Call	Explanation
concat(str1, str2)	Returns a single string consisting of str1 followed by str2. For example, concat("key", "board") returns "keyboard".
prefix(str, length)	Returns the first length characters of str or str if length is greater than the number of characters in str. For example, prefix("delivery", 3) returns "del" and prefix("delivery", 100) returns "delivery".
The variable initials is to be assigned a string consisting of the first letter of the string firstName followed by the first letter of the string lastName. Which of the following assigns the correct string to initials ?

- I said C for this question but the correct answer was A, because C's statement concatenates firstName and lastName and then assigns the first character of the result (which is the first character of firstName) to initials, which is wrong.

### Question 47

Consider the following code segment.

The figure presents twelve blocks of code that consist of  12 total lines. Line 1: [begin block] a  ← 10 [end block] Line 2: [begin block] b  ← 20 [end block] Line 3: [begin block] c  ← 30 [end block] Line 4: [begin block] d  ← 40 [end block] Line 5: [begin block] x  ← 20 [end block] Line 6: [begin block] b  ← x plus b [end block] Line 7: [begin block] a  ← x plus 1 [end block] Line 8: [begin block] d  ← c plus d divided by 2 [end block] Line 9: [begin block] DISPLAY [begin block] a [end block] [end block] Line 10: [begin block] DISPLAY [begin block] b [end block] [end block] Line 11: [begin block] DISPLAY [begin block] c [end block] [end block] Line 12: [begin block] DISPLAY [begin block] d [end block] [end block]
What is displayed as a result of executing the code segment?

- I said A for this question but the correct answer was D, because the values of a, b, and d are updated after they are initially assigned values.

### Question 46

Consider the following code segment.

The figure presents four blocks of code that consist of 4 lines. Line 1: [begin block] first ← true [end block] Line 2: [begin block] second ← false [end block] Line 3: [begin block] second ← first [end block] Line 4: [begin block] first ← second [end block]
What are the values of first and second as a result of executing the code segment?

- I said B for this question but the correct answer was A, because the third statement assigns the value of first (which is true) to second.

### Question 45

Consider the following code segment.

theList ← [-2, -1, 0, 1, 2]
count1 ← 0
count2 ← 0
FOR EACH value IN theList

{
IF(value > 0)
{
count1 ← count1 + 1
}
ELSE
{
count2 ← count2 + 1
}
}

What are the values of count1 and count2 as a result of executing the code segment?

- I said A, but the answer was B because the code segment iterates through each element in the list, incrementing count1 for each positive value and incrementing count2 otherwise. There are three nonpositive values in the list, so count2 is 3.

### Question 43

Consider the following code segment.

The figure presents three blocks of code that consist of 5 total lines. Throughout the third block of code are nested blocks of code. Line 1: [begin block] x ← 0 [end block] Line 2: [begin block] result ← 0 [end block] [Begin Block] Line 3: REPEAT UNTIL [begin block] x is greater than 5 [end block] [Begin Block] Line 4: [begin block] result ← result plus x [end block] Line 5: [begin block] x ← x plus 1 [end block] [End Block] [End Block]
What is the value of result after the code segment is executed?

- I said A, but the answer was C because the variables x and result are initialized to 0. Inside the loop, result is increased by x and x is increased by 1. The loop terminates when x exceeds 5. Therefore, result is assigned the sum of the integers from 0 to 5, or 15.

### Question 39

The list wordList contains a list of 10 string values. Which of the following is a valid index for the list?

- I said B, but the answer was D because while the list elements are strings, the indices of a list are typically nonnegative integers.

### Question 35

In a certain video game, the variable maxPS represents the maximum possible score a player can earn. The maximum possible score depends on the time it takes the player to complete the game. The value of maxPS should be 30 if time is greater than 120 and 50 otherwise.

Which of the following code segments correctly sets the value of maxPS based on the value of time ?

- I said A and C, but it is actually A and D because this code segment assigns maxPS the value 50 when time > 120 and assigns maxPS the value 30 otherwise.

### Question 31

Assume that both lists and strings are indexed starting with index 1.

The list wordList has the following contents.

["abc", "def", "ghi", "jkl"]

Let myWord be the element at index 3 of wordList. Let myChar be the character at index 2 of myWord. What is the value of myChar ?

- I said B but it was C because the character "f" is the character at index 3 of the string element at index 2 in wordList, and the element at index 3 in wordList is "ghi". The character at index 2 of "ghi" is "h".

### Question 16

Which of the following best explains how messages are typically transmitted over the Internet?

- I said A but it was B because messages are broken into packets, but they can be received in any order and still be reassembled.
