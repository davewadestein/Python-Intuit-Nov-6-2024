# Python-Intuit-Nov-6-2024

## Course Evaluation Link
* https://docs.google.com/forms/d/e/1FAIpQLSdVjTtollu_M2QJGnFWmWQGGzsIwL0AxgJt75Kbu08cXayUIQ/formrestricted

## What to do next?
* clean up Roman numeral solution and if desired, make it work for the more complicated Roman numerals (subtraction)
   * here is an algorithm you can use to solve it (but there are plenty of other ways to do it)
     1. iterate thru the Roman numeral and put the Hindu/Arabic value into a list,<br>
          e.g., __`MCMXCIX`__ => __`[1000, 100, 1000, 10, 100, 1 10]`__
     2. iterate thru the Hindu/Arabic values, comparing each number with its neighbor, e.g.,
          compare 1000 to 100, 100 to 1000, 1000 to 10, etc.
     3. if a number is LESS THAN its neighbor, make that number negative, so your list would now look like this:
          __`[1000, -100, 1000, -10, 100, -1 10]`__ (because 100 < 1000, 10 < 100, and 1 < 10)
     4. Now sum up the numbers in the list (for this example, you'll get 1999)
  
## Resources
* [Python Tutor](https://pythontutor.com)
* [MyPy](https://mypy-lang.org/)
  
## How to reach me...
* dave@developintelligence.com
