# Ruby: Perfect Numbers

The Greek mathematician Nicomachus devised a classification scheme for natural numbers.

The Greek mathematican Nicomachus devised a classification scheme for
natural numbers, identifying each as belonging uniquely to the
categories of _abundant_, _perfect_, or _deficient_.  A perfect number
equals the sum of its positive divisors — the pairs of numbers whose
product yields the target number, excluding the number itself.

- Perfect: Sum of factors = number
- Abundant: Sum of factors > number
- Deficient: Sum of factors < number

The Aliquot sum is defined as the sum of the factors of a number not
including the number itself.

## Examples

- 6 is a perfect number because its divisors are 1, 2, 3 and 6 = 1 + 2 +
  3.
- 28 is perfect number because 28 = 1 + 2 + 4 + 7 + 14.
- Prime numbers 7, 13, etc are Deficient by the Nicomachus
  classification.

The tests use the Minitest testing framework. To install it run the command:

    gem install minitest

Run the tests with the `ruby` command:

    ruby perfect_numbers_test.rb

## Resources

If you have never used Minitest, check out [Intro to TDD][tdd] tutorial from Jumpstart Lab.

[tdd]: http://tutorials.jumpstartlab.com/topics/testing/intro-to-tdd.html

## Source

Taken from Chapter 2 of Functional Thinking by Neal Ford. [http://shop.oreilly.com/product/0636920029687.do](http://shop.oreilly.com/product/0636920029687.do)

This exercise is from the [Ruby][ruby] track on [Exercism][exercism]

[exercism]: http://exercism.io
[ruby]: http://exercism.io/languages/ruby



