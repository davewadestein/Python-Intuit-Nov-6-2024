# Python-Intuit-Nov-6-2024

* No 4th day, unfortunately, I have just been informed
* Feel free to reach out if the below is unclear or you want more ideas
  
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

* do the word counting exercise from Part 2...File I/O + dicts:
  * write a Python program to read a file and count the number of occurrences of each word in the file
  * use a __`dict`__, indexed by word, to count the occurrences
  * remember __`d.get(key, 0)`__ will return __`0`__ if there is no such key in the dict (vs. __`d[key]`__ which will throw an exception) and also the __`in`__ operator
  * treat __The__ and __the__ as the same word when counting
  * print out words and counts, from most common to least common
  * __EXTRA:__ remove punctuation, so __Hamlet,__ == __Hamlet__ # refer back to "import this"
  * The Road Not Taken and Hamlet are in your materials
 
* "Fun" games you can code up in Python (not everyone agrees on the meaning of "fun")
   * [Cows and Bulls](https://en.wikipedia.org/wiki/Bulls_and_cows)
      * I like this game because it's not a lot of code to write, but it exercises some useful Python features
      * How do you generate and store the code, is an important question
   * [Chutes and Ladders](https://en.wikipedia.org/wiki/Snakes_and_ladders)
      * use the Chutes and Ladders gameboard as your guide
         * notice that, for e.g., if you land on square 1, you take a ladder up to 38, and as another example, if you land on square 87, you take a chute down to 24...so you have to have a way to know which board squares cause the player to move up or down vs. just landing on that square
    
## Resources
* [Python Tutor](https://pythontutor.com)
* [MyPy](https://mypy-lang.org/)
  
## How to reach me...
* dave@developintelligence.com
