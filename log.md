# 100 Days Of Code - Log

Why 100 Days of Code for me?
I've always enjoyed the idea of programming/coding/developing, whatever you want to call it. In some of my previous job roles, I have done a decent amount of coding, but am completely self taught - so there are gaps. For the past several years I have managed a team of web developers, but in this role I am strictly a manager. Not much opportunity to get my hands dirty and write code.  

Additionally, my kid is showing signs of interest, so I figured this would be a good time to take a few steps back and explore different languages, frameworks, etc. and maybe bring him along for the ride. 

### Day 1: November 24, Sunday

**Today's Progress**: Created a basic compound interest calculator in Python.

**Thoughts** After explaining compound interest to the kid, I developed a bare-bones compound interest calculator. Asks for the user's input for principal, interest rate, time invested, and how often it should be compounded in a year. It walks through each step in the calculation, shows the final amount, then prompts to run it again with different values. 

Still plenty of room for improvement; need to add error handling and the option for additional investments over time. 

**Link(s) to work**
1. [Compound Interest Calculator](https://github.com/lanedenson/compound-interest-calculator/blob/main/interest.py)

### Day 2: November 25, Monday

**Today's Progress**: Created a stripped down version of the compound interest calculator in Python.

**Thoughts** Created a new variation of the calculator that removes the walkthrough explanation; also added the calculation as a function rather than doing the math inline.

**Link(s) to work**
1. [Compound Interest Calculator](https://github.com/lanedenson/compound-interest-calculator/blob/main/interest-less-detail.py)

### Day 3: November 26, Tuesday

**Today's Progress**: Converted the compound interest calculator to BASIC. 

**Thoughts** Because I am a fan of retro-computing, I recreated the calculator in Microsoft BASIC for the Commodore 64. I think I spent more time trying to format the text to fit a 40 column fixed width screen than anything else! The calculations are a little bit off due to limited floating-point precision. There may be ways to address this; may look into it later.  

**Link(s) to work**
1. [Raw PRG file - should work natively on Commodore 8-bitters](https://github.com/lanedenson/compound-interest-calculator/blob/main/compoundinterest.prg)
2. [BASIC program exported to a .bas file](https://github.com/lanedenson/compound-interest-calculator/blob/main/compound-interest.bas)

### Day 4: November 27, Wednesday

**Today's Progress**: Started work on JavaScript variant

**Thoughts** The goal is to make this a web page that will take the inputs via an on screen form, do the math, plot a graph, etc. For now, this is is just a straight port of the Python version. Not completed yet.

**Link(s) to work**
1. [JavaScript version](https://github.com/lanedenson/compound-interest-calculator/blob/main/interest-less-detail.js)

### Day 5: November 28, Thursday

**Today's Progress**: Made improvements to Python scripts

**Thoughts** Updated the Python scripts to do some error handling on the inputs, added docstrings to functions for documentation purposes

**Link(s) to work**
1. [GitHub Repo](https://github.com/lanedenson/compound-interest-calculator)

### Day 6: November 30, Saturday

**Today's Progress**: Made additional improvements to Python scripts

**Thoughts** Moved the error checking to it's own helper function, rather than having the same error checking logic in both float and integer inputs.

**Link(s) to work**
1. [GitHub Repo](https://github.com/lanedenson/compound-interest-calculator)

### Day 7: December 1, Sunday

**Today's Progress**: Started work on monthly contributions

**Thoughts** Started work on adding monthly contributions to the function. Really too complex to keep in a single equation, so I'm going to use the approach I started in interest.py to step through each part of the equation, creating variables for each step. That way I can reuse some of the common portions, such as the rate per period and total periods.

**Link(s) to work**
1. [GitHub Repo](https://github.com/lanedenson/compound-interest-calculator)

