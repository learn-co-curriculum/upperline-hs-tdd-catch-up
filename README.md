
##Test Driven Development in a Nutshell
<img src="https://s3.amazonaws.com/after-school-assets/tdd.png">
**Test Driven Development** is _a practice that developers use to build high quality programs and prevent errors from developing in their programs_. Before a single line of code gets written, developers write tests _first_. The number one reason this is an important practice is because tests minimize the amount of errors and bugs in the code. It seems counterintuitive to write tests first, but there are a few reasons why developers work this way:

1. **Design** TDD force you to think about the design of your code before you write it. It's easy to jump right into implementing the features of your application, but stopping to think about how exactly you want your code to function makes for well-designed and thoughtful programs.

2. **Discipline** If you don't write tests _first_, you might never get around to writing them period. It might feel like a chore to write tests first, but you'll be glad at the end of the day that you have a full suite of tests to keep your code running smoothly and bug-free.

3. **Less Work** By repeating the process of 1: write test, 2: write code to make the test pass, where developers write one test then write the actual code to run the test on, developers end up writing only the code they need. It's an arduous process, so superfluous code comes with a lot of baggage (more tests!). Thus, developers ultimately only write the code that's wholy necessary.


##How It Works
The typical test development cycle can be summed up with "red, green, refactor." **Red**: write a test and run it. It fails because you haven't written the actual program code to make it work! **Green**: Write your code, and make the test pass. **Refactor**: look at the code and see if you can make it any better.

1. **Write a test** to describe a small feature you want to build. When you run the test, it'll fail. (That's the red part.)
2. **Write just enough code** to make the test pass. Now when you run the test, it should pass. (This is the green part.)
3. **Refactor** your code. Make that code as succinct, clear, and DRY as possible. Refactor as necessary and retest.
4. **Rinse and repeat!**

##Rspec - A Ruby Testing Framework
Tests are written using a program called Rspec (among others), and the tests can be found in files _ending_ in `_spec.rb`. For example, if you have a ruby file called `test.rb`, the tests would be written in a file called `test_spec.rb`.

To run tests, first make sure you have rspec installed - type `gem install rspec` in your terminal. Then go to the root of your project and type `rspec` - The tests will run and you'll see the failures that you have to work on.

Failures are good. Let me repeat: **failures are good**. They are part of step 1 in the TDD process, and they are breadcrumbs on the path to success. Read the failures carefully, change your code, and run `rspec` again until everything is passing.

##Try It Out For Yourself
Try working through the tests in [test-first ruby](http://testfirst.org/learn_ruby). It gets progressively harder, so don't get discouraged if you feel stuck!

##Note
In this course, we will **not** be writing our own tests. Instead, the tests will be written for you, and you have to write the appropriate code to get them to pass. So, it's a truncated approach to TDD, but one that gets you acquainted with the process in general.

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/hs-tdd-catch-up' title='Test Driven Development in a Nutshell'>Test Driven Development in a Nutshell</a> on Learn.co and start learning to code for free.</p>
