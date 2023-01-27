## Chapter 1
+ As they added more and more features, the code got worse and worse until they simply could not manage it any longer.
+ LeBlanc’s law: _Later equals never_.
+ So too it is unprofessional for programmers to bend to the will of managers who don’t understand the risks of making messes.
+ In short, they don’t take the time to go fast!
+ Clean code does one thing well.
+ It should contain only what is necessary.
+ Clean code always looks like it was written by someone who cares. 
+ You can call it beautiful code when the code also makes it look like the language was made for the problem.
+ Leave the campground cleaner than you found it. - Boy Scout rule
+ Improve a little bit of code before you leave.

## Chapter 2
+ Avoid naming single letter variables.
+ Class name should be noun
+ Method names should be verbs
+ Dont' name things in whacky way
+ Don't use the same name to convey two different concepts.
+ Our goal, as authors, is to make our code as easy as possible to understand.
+ So go ahead and use computer science (CS) terms, algorithm names, pattern names, math terms, and so forth.
+ Add no more context to a name than is necessary.

## Chapter 3
+ Junit is an open source unit testing tool for Java.
+ Functions should  be small
+ Functions should not be 100 lines long. Functions should hardly ever be 20 lines long.
+ Every function in _this_ program was just two, or three, or four lines long. Each was transparently obvious. Each told a story. And each led you to the next in a compelling order.
+ `if` statements, `else` statements, `while` statements, and so on should be one line long.
+ FUNCTIONS SHOULD DO ONE THING. THEY SHOULD DO IT WELL. THEY SHOULD DO IT ONLY.
+ another way to know that a function is doing more than “one thing” is if you can extract another function from it with a name that is not merely a restatement of its implementation
+ One level of Abstraction per function
+ The Stepdown rule
+ Single Responsibility Principle: Every class should have a single responsibility or single reason to change.
+ niladic - a function having zero arguments
+ Passing a boolean into a function is a truly terrible practice.
+ Side effects are lies.
+ In general output arguments should be avoided.

## Chapter 4
+ Comments are necessary evil.
+ A clean code programmer use comments as less as possible.

## Chapter 5
+ The functionality that you create today has a good chance of changing in the next release, but the readability of your code will have a profound effect on all the changes that will ever be made.
+ Indentation

## Chapter 6


## Chapter 7
+ Error handling is important, _but if it obscures logic, it’s wrong_.
+ Use Unchecked Exceptions
+ wrapping third-party APIs is a best practice.
+ Often a single exception class is fine for a particular area of code.
+ Don't return null. It creates extra work for the caller. consider throwing an exception or returning a SPECIAL CASE object instead.
+ Clean code is readable, but it must also be robust.
+ see error handling as a separate concern.

## Chapter 8
+ You should not pass interface at the boundary.
+ Learning about 3rd party API via writing tests.
+ boundary tests
+ Interesting things happen at boundaries

## Chapter 9
