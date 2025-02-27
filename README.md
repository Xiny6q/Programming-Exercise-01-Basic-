Download link :https://programming.engineering/product/programming-exercise-01-basic-java-2/


# Programming-Exercise-01-Basic-
Programming Exercise 01 – Basic
Authors: Daniel

Topics: variables, assignments, expressions, comments

Problem Description

This assignment will assess your knowledge of variables, expressions, assignment, classes, and String output.

There are two parts:

1. Calculate how fast you are driving (Speedometer.java).

2. Calculate how much money you have left after buying groceries (GroceryShopping.java).

Solution Description

Part 1: Speedometer

1. Create a class called Speedometer.

2. Add a comment (block or single-line) in your class and write your name and a fun fact about you.

3. Create the main method inside the Speedometer class – all the next steps will be inside the main method.

4. Create a variable named kilometers and assign to it a value of 50.

◦ The type of this variable should be the default type used for integer literals.

5. Create a variable named kmPerMile and assign to it a value of 1.60934.

◦ The type of this variable should be the default type used for floating-point literals.

6. Create a variable named hours and assign to it a value of 0.54.

◦ The type of this variable should be the default type used for floating-point literals.

7. Create a String variable named name and assign to it your name.

8. Store how many miles you will travel into a variable of appropriate type named miles, calculated using the following formula:

◦ miles = kilometers / kmPerMile

9. Create a variable named milesTrunc of appropriate type for the following calculation. Using the miles variable calculated above, “truncate” the decimal portion to three decimal places. You must use basic arithmetic operators (*, /) and casting to accomplish this. Keep in mind that casting is NOT rounding (e.g., 3.5419 truncated to three decimal places is 3.541).

◦ Hint: Think about how we can “move” a decimal point left or right, and how we can remove the digits following the decimal point.

10. Create a variable named speed of appropriate type for the following calculation. Using the milesTrunc and hours variables, calculate the speed by dividing milesTrunc by hours, and truncate the result of the division to two decimal places. You must use basic arithmetic operators (*, /) and casting to accomplish this.

 

11. Finally, use the following statement (type it out, do not copy and paste) to print how fast you were driving:

System.out.println(name + “ drove at a speed of ” + speed + “ mph for ” + milesTrunc + “ miles!”);

The output should be as follows, but with your name at the beginning of the line:

Daniel drove at a speed of 57.53 mph for 31.068 miles!

 

Part 2: Grocery Shopping

1. Create a class called GroceryShopping.

2. Create the main method inside the GroceryShopping class – all the next steps will be inside the main method.

3. Create a variable named bananaCost and assign to it a value of 3.99.

◦ The type of this variable should be the default type used for floating-point literals.

4. Create a variable named applesCost and assign to it a value of 1.25.

◦ The type of this variable should be the default type used for floating-point literals.

5. Create a variable named numApples and assign to it a value of 4.

◦ The type of this variable should be the default type used for integer literals.

6. Create a variable named couponValue and assign to it a value of 0.53.

◦ The type of this variable should be the default type used for floating-point literals.

7. Create a variable named taxRate and assign to it a value of 0.08.

◦ The type of this variable should be the default type used for floating-point literals.

8. Create a variable named orderTotal and assign to it a value of 0.0.

◦ The type of this variable should be the default type used for floating-point literals.

9. Using compound assignment operators (+=, -=, etc.), perform the following calculations to orderTotal. Use one compound assignment operator per statement.

a. Add bananaCost divided by 2 (you buy one bundle of bananas that were 50% off!).

b. Add applesCost multiplied by numApples (you buy numApples apples).

c. Subtract couponValue multiplied by 3 (you apply three coupons to your purchase).

d. Multiply by 1 + taxRate (you pay sales taxes).

10. Create a variable named orderTotalTrunc of appropriate type and assign to it the value of orderTotal truncated to two decimal places. You must use basic arithmetic operators (*, /) and casting to accomplish this.

11. Use the following statement (type it out, do not copy and paste ) to print the total cost of the order:

System.out.println(“Your order total is $” + orderTotalTrunc + “.”);

12. Create a variable named dollars and assign to it a value of 10.

◦ The type of this variable should be the default type used for integer literals.

13. Using a compound assignment operator, subtract orderTotalTrunc from dollars.

 

14. Use the following statement (type it out, do not copy and paste) to print out the dollars you have remaining:

System.out.println(“You have ” + dollars + “ dollar bills remaining.”);

15. With the given numbers, the output should look like the following:

Your order total is $5.83.

You have 4 dollar bills remaining.

 

Turn-In Procedure

Submission

To submit, upload the files listed below to the corresponding assignment on Gradescope:

• Speedometer.java

• GroceryShopping.java

Make sure you see the message stating the assignment was submitted successfully. From this point, Gradescope will run a basic autograder on your submission as discussed in the next section. Any autograder tests are provided as a courtesy to help “sanity check” your work and you may not see all the test cases used to grade your work. You are responsible for thoroughly testing your submission on your own to ensure you have fulfilled the requirements of this assignment. If you have questions about the requirements given, reach out to a TA or Professor via the class forum for clarification.

You can submit as many times as you want before the deadline, so feel free to resubmit as you make substantial progress on the assignment. We will only grade your latest submission. Be sure to submit every file each time you resubmit.

Gradescope Autograder

If an autograder is enabled for this assignment, you may be able to see the results of a few basic test cases on your code. Typically, tests will correspond to a rubric item, and the score returned represents the performance of your code on those rubric items only. If you fail a test, you can look at the output to determine what went wrong and resubmit once you have fixed the issue.

The Gradescope tests serve two main purposes:

• Prevent upload mistakes (e.g., non-compiling code)

• Provide basic formatting and usage validation

In other words, the test cases on Gradescope are by no means comprehensive. Be sure to thoroughly test your code by considering edge cases and writing your own test files. You also should avoid using Gradescope to compile, run, or Checkstyle your code; you can do that locally on your machine.

Other portions of your assignment can also be graded by a TA once the submission deadline has passed, so the output on Gradescope may not necessarily reflect your grade for the assignment.

 

Allowed Imports

To prevent trivialization of the assignment, you may not import any classes for this assignment.

Feature Restrictions

There are a few features and methods in Java that overly simplify the concepts we are trying to teach or break our autograder. For that reason, do not use any of the following in your final submission:

• var (the reserved keyword)
• System.exit

• System.arraycopy

Collaboration

Only discussion of the assignment at a conceptual high level is allowed. You can discuss course concepts and assignments broadly; that is, at a conceptual level to increase your understanding. If you find yourself dropping to a level where specific Java code is being discussed, that is going too far. Those discussions should be reserved for the instructor and TAs. To be clear, you should never exchange code related to an assignment with anyone other than the instructor and TAs.

Important Notes (Don’t Skip)

• Non-compiling files will receive a 0 for all associated rubric items.

• Do not submit .class files.

• Test your code in addition to the basic checks on Gradescope.

• Submit every file each time you resubmit.

• Read the “Allowed Imports” and “Restricted Features” to avoid losing points.

• Check on Ed Discussion for a note containing all official clarifications and sample outputs.

It is expected that everyone will follow the Student-Faculty Expectations document and the Student Code of Conduct. The professor expects a positive, respectful, and engaged academic environment inside the classroom, outside the classroom, in all electronic communications, on all file submissions, and on any document submitted throughout the duration of the course. No inappropriate language is to be used, and any assignment deemed by the professor to contain inappropriate offensive language or threats will get a zero. You are to use professionalism in your work. Violations of this conduct policy will be turned over to the Office of Student Integrity for misconduct.

 

 

 

 

 

 
