# INTRODUCTION TO ELIXIR LANGAGUE

The goal of this workshop is you initiate you to the simple basis of the Elixir language.

## MUST HAVE

In order to be able to work on this, you should install Elixir, check here how you can install it : `https://elixir-lang.org/install.html#distributions`.

# STEP 1: CREATE YOUR FIRST ELIXIR PROJECT

Now that you have installed Elixir packages, you should be able to create your first Elixir project !

Use the following command to create a new project: `mix new project-name`

It will generate multiple file & folders, but we will focus on one file which is named: `lib/proj.ex`.

Then, you can test the default function `hello` that is generated in the previous file, which, when called, will print `world`.

To test it, you will have to use the following command: `iex -S mix`. This brings you into an Elixir shell.

As you could've seen in the `lib/proj.ex`, the function in encapsuled in a *defmodule Proj*.

Now to test a function that is in your module, you will have to call the module and the function, it should be something like this: `Proj.hello`. The outpout should be `world`.

Know that when you add a new function, you can do `recompile` command in the shell to recompile everything that is in your project, so you can test the new function without going back to your terminal's shell and do again the command to get into Elixir's shell.

Now you know how to test your functions, let's start to work on it.

# STEP 2: EASY

**NOTE**
You should maybe take a look at the documentation to become more familiar with the syntax.

`https://hexdocs.pm/elixir/Kernel.html`

## Exercise 1:

*Let's use numbers*

Write a function that takes a list of integers and returns the largest number in the list.

## Exercise 2:

Write a function that takes a list of integers and returns a new list with all the even numbers in the original list.

## Exercise 3:

Write a function that takes a list of integers and returns the sum of all the even numbers in the list.

## Exercise 4:

Write a function that takes a list of integers and returns the average of all the numbers in the list.

## Exercise 5:

*Let's use strings now*

Write a function that takes a string as input and returns the reverse of that string.

## Exercise 6:

Write a function that takes a list of strings and returns the length of the longest string in the list.

## Exercise 7:

Write a function that takes a string and returns a new string with all the vowels removed.

## Exercise 8:

Write a function that takes a list of strings and returns a new list with all the strings that start with the letter given in input.

# STEP 3: NORMAL

## Exercise 1:

Write a function that takes an integer as input and returns the sum of its digits.

## Exercise 2:

Write a function that takes an integer as input and does the Fibonacci sequence up to the nth term. 

**NOTE**
The Fibonacci sequence is a series of numbers in which each number is the sum of the two preceding ones, starting with 0 and 1.
For example, if the input is 8, the output should be [0, 1, 1, 2, 3, 5, 8, 13].

## Exercise 3:

Write a function that takes a string as input and counts the number of vowels in the string without caring about the case.

## Exercise 4:

Write a function that takes a string as input and returns true or false if it is a palindrome or not.

**NOTE**
A palindrome is a word, phrase that reads the same forward and backward.
For example: "level" is a palindrome, and "hey" is not.

# STEP 3: HARD

## Final exercise:

Write a function that will take a string in parameter and then returns a list of lists with all the anagrams in lists of the list.

**NOTE**
An anagram is a word that has all the same letter in common with an another word.
For example: `heart - earth`.