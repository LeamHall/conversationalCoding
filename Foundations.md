# Foundations

The Foundation section focuses on the foundational tasks of the language;
the building blocks. This is the one you should start with, and stick with,
until you can do it fluently. When you're up to 80%, move on to the next
task, but keep doing this one every couple of days until you have it right.

Open your heart and mind to learning. Don't beat yourself up if
you don't do everything perfectly the first time out.
I didn't, and I'm writing the thing...

## Package structure

Create a file called foundations.go

Declare the package main.
Add a descriptive comment for each item.

Import something that allows printing, and something for errors.

## Package level constructs

### Variables and Types

Define a struct that has a string.

Define a string outside of the main function.

### Functions and Methods

Define a function that takes an int and returns it doubled.
Return an error if the int is 5.

Define a function that takes a string, and returns "Hello " and the string.

Define a method that returns the string from the struct.


## Main

Start the main function.

### Simple variables

Define a variable that uses the global string.
  Print the variable.

### Errors
Using the function that doubles ints, pass in 5 and handle the error.

### Blocks and iteration
Write a for loop that counts from 5 to 18.
  Have it print something funny at 7 and 17.

### Composite types
Define a variable of the global struct.
  Assign a string to the string attribute
  Call the method and print the string.

Make an slice of a few numbers.
  Write a for loop that iterates over the slice and prints the number doubled.

Using three people you know, make a map with their name as the key, and 
describe the relationship as the value.
  Using range, iterate over the map and print each key and value.

### Wrap up

Make a copy of the file as is, and then run go fmt on the copy. See what 
changes.

Delete the files. If you missed more than one thing, do it again tomorrow.  :)

