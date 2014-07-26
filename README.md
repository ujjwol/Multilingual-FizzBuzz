Multilingual-FizzBuzz
=====================

Trying to write FizzBuzz in as many languages as I can whenever I'm bored.

==Solutions to FizzBuzz in Different Languages for Fun==

Write a program that prints the integers from 1 to 100. But for multiples of three print "Fizz" instead of the number and for the multiples of five print "Buzz". For numbers which are multiples of both three and five print "FizzBuzz".

Solution
We loop from 1 to 100, and then each time whether the number is multiple of three or five or both or none. For example, to check whether 9 is multiple of 3 or not we divide 9 by 3 which gives us 3 with remainder 0. If the division results 0 remainder than the number is multiple of number divided by. Many programming languages provide a easier way to check the remainder in the form of modular division. For example, in Java 9 % 3 gives the remainder of the division 9 by 3. We can use this modular division to write our fizz buzz program.

Check
Simply pipe the output of your program to diff and comapre it with expect_output.txt by

[code]
ujjwol@mycomputer:Fun/FizzBuzz$ ./Node.Js/FizzBuzz.js | diff expected_output.txt -
ujjwi@mycomputer:Fun/FizzBuzz$
[code]

Nothing outputted means, there is no difference hence, the FizzBuzz matches the expected output.
