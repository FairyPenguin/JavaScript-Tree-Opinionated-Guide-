# JavaScript Tree 🌳 [Opinionated-Guide]

![](/assets/pexels-luci-8793629-modified.jpg)

img source: [https://www.pexels.com/photo/close-up-photo-of-a-green-iguana-8793629/]

This guide i created while my journey for learning JavaScript, and as there many guides and cheatsheets so i decided only to focus on two things:

1- The parts that i feel it need more depth and more learning to fully understand, some will seem to you a very easy ones but for me i see a diffrent POV.

2- The Weired Parts [NaN - Undefined - truthy - Falsy - etc ........]

#I will updated the guide regulary 

---

1- Comments:

// inline comment [a comment in the same line with the code]

/* multi
       line
           comment */
           
---

2- Varibales initial value
When JavaScript variables are declared, they have an initial value of undefined. If you do a mathematical operation on an undefined variable your result will be NaN which means "Not a Number". If you concatenate a string with an undefined variable, you will get a string of undefined. [Source:https://www.freecodecamp.org/]

---

3- camelCase && caseSenstive

🐫🐪 thisISACamelCaseSentenceWatchTheFirstLetterInEveryWordExceptTheFirstWord

 myVar !== MYVAR

---

4- Constant

const = let + read-only(cannot be reassigned)

const has all the awesome features that let has, with the added bonus that variables declared using const are read-only. They are a constant value, which means that once a variable is assigned with const, it cannot be reassigned:

---

5- let value can be changed but not re declared like:

![](/assets/let-reassign.png)

---

6- Increment:

You can easily increment or add one to a variable with the ++ operator.

i++;  is the equivalent of  i = i + 1;

Note: The entire line becomes i++;, eliminating the need for the equal sign.

---

7- Float

Decimal numbers are sometimes referred to as floating point numbers or floats.

---

8-  % === The remainder operator

The remainder operator % gives the remainder of the division of two numbers.

Example

5 % 2 = 1 because
Math.floor(5 / 2) = 2 (Quotient)
2 * 2 = 4
5 - 4 = 1 (Remainder)

---

9- String Immutability


In JavaScript, String values are immutable, which means that they cannot be altered once created.

Use Bracket Notation to Find the Last Character in a String

In order to get the last letter of a string, you can subtract one from the string's length.
Unlike strings, the entries of arrays are mutable and can be changed freely, even if the array was declared with const.

---

10- Nest one Array within Another Array

This is also called a multi-dimensional array.


---

11- Modify Array Data With Indexes

Unlike strings, the entries of arrays are mutable and can be changed freely, even if the array was declared with const.

---

12- Parameters && Arguments

Parameters are variables that act as placeholders for the values that are to be input to a function when it is called. When a function is defined, it is typically defined along with one or more parameters. The actual values that are input (or "passed") into a function when it is called are known as arguments.

---
