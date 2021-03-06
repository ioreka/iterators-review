# Iterators review
This review uses seed data and objectives outlined by the Flatiron School, put into a standalone repo to help students practice their Ruby.
## Practice using the following two arrays in IRB and complete all the objectives. This is a ReadMe, not a lab, so there are no tests to run. Mess around with the arrays and iterators until you are comfortable with using them!

### Using a numeric array

Array of 1 - 100 = `(0..100).to_a`

Objectives:

- return all odd numbers
- return all even numbers
- return the square of all the numbers
- return the first number whose square is > 350
- return all the numbers whose square is > 350
- return all the numbers, cubed
- return the first number whose cube is > 500
- return all the numbers whose cube is < 500

For reference:

- `x ** 2` is x squared
- `x ** 3` is x cubed
- `x.odd?` checks if x is odd
- `x.even?` checks if x is even


### Using an array of strings/chars

Array from 'a' to 'z' =`('a'..'z').to_a`

Objectives:

- return all the letters, capitalized
- first letter with ord > 120
- all the letters whose capital is > 72
- all letters where the capital has an even ord
- all letters with odd ord
- first odd - ord letter with ascii value > 80

For reference: letter.ord - returns the ascii value of a letter
