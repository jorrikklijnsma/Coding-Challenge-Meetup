# JavaScript Coding Challenges

## 1 **Array Manipulation:**

### 1.1 Merge and Sort Arrays

**Description:** Write a function that takes two arrays of numbers as inputs, merges them into one array, and then sorts the merged array in ascending order.
**Example:** `mergeSortArrays([3, 1], [4, 2])` should return `[1, 2, 3, 4]`.
**Test/Mockup Data:** Use arrays like `([10, 6], [7, 12, 5])`, `([], [3, 4, 5])`.

### 1.2 Zeroes to the End

**Description:** Create a function that moves all zeroes in an array to the end without changing the order of non-zero elements.
**Example:** `moveZeroes([0, 1, 0, 3, 12])` should return `[1, 3, 12, 0, 0]`.
**Test/Mockup Data:** Test with `[0, 1, 0, 0, 1, 2, 0, 3]`, `[1, 2, 3, 4]`.

### 1.3 Remove Duplicates

**Description:** Create a function that removes all duplicate values from an array.
**Example:** `removeDuplicates([1, 2, 2, 3, 4, 4])` should return `[1, 2, 3, 4]`.
**Test/Mockup Data:** Test with `[1, 1, 1, 2, 3]`, `[5, 4, 5, 4, 3, 3, 2]`.

### 1.4 Find the Missing Number

**Description:** Write a function that finds the missing number in a sequence of consecutive numbers.
**Example:** `findMissing([3, 4, 6, 7, 8])` should return `5`.
**Test/Mockup Data:** Use sequences like `[1, 2, 4, 5]`, `[10, 11, 12, 14, 15]`.

### 1.5 Rotate Array

**Description:** Implement a function to rotate an array to the right by `k` steps, where `k` is a non-negative number.
**Example:** `rotateArray([1,2,3,4,5], 2)` should return `[4, 5, 1, 2, 3]`.
**Test/Mockup Data:** Test with `([1, 2, 3, 4, 5, 6, 7], 3)`, `([1], 0)`.

## 2 **Geometric Calculations:**

### 2.1 Calculate Circle Area

**Description:** Write a function that takes the radius of a circle as input and returns the area of the circle.
**Example:** `circleArea(2)` should return approximately `12.57`.
**Test/Mockup Data:** Test with radii like `5`, `3.5`.

### 2.2 Point Inside Rectangle

**Description:** Create a function that takes a rectangle (as four coordinates) and a point (as x and y), and checks if the point lies inside the rectangle. Assume the rectangle sides are parallel to the axes.
**Example:** `isInsideRectangle({x1: 1, y1: 1, x2: 4, y2: 3}, {x: 2, y: 2})` should return `true`.
**Test/Mockup Data:** Test with `{x1: 0, y1: 0, x2: 5, y2: 5}` and points like `{x: 1, y: 1}`, `{x: 6, y: 6}`.

### 2.3 Calculate Triangle Perimeter

**Description:** Write a function that takes the lengths of the three sides of a triangle and returns its perimeter.
**Example:** `trianglePerimeter(3, 4, 5)` should return `12`.
**Test/Mockup Data:** Test with side lengths like `(1, 2, 2.5)`, `(5.5, 6.5, 7.5)`.

### 2.4 Determine Quadrilateral Type

**Description:** Create a function that takes the lengths of the four sides of a quadrilateral and returns whether it is a square, rectangle, or other quadrilateral.
**Example:** `quadrilateralType(4, 4, 4, 4)` should return `"Square"`.
**Test/Mockup Data:** Use `(2, 2, 3, 3)`, `(3, 4, 5, 6)`, `(5, 5, 5, 5)`.

### 2.5 Coordinate Plane Quadrant Finder

**Description:** Implement a function that takes an (x, y) coordinate pair and determines which quadrant of the coordinate plane the point lies in.
**Example:** `findQuadrant(2, -3)` should return `"Quadrant IV"`.
**Test/Mockup Data:** Test with points like `(-1, 5)`, `(0, -3)`, `(-4, -4)`.

## 3 **String Editing and Manipulation:**

### 3.2 Palindrome Checker

**Description:** Write a function that checks whether a given string is a palindrome (reads the same forward and backward). The check should be case-insensitive and ignore spaces.
**Example:** `isPalindrome("Race car")` should return `true`.
**Test/Mockup Data:** Test with strings like `"hello"`, `"A man a plan a canal Panama"`.

### 3.3 Vowel Count

**Description:** Write a function that returns the number of vowels in a given string.
**Example:** `countVowels("hello world")` should return `3`.
**Test/Mockup Data:** Test with strings like `"example"`, `"AEIOU"`.

### 3.4 String Compression

**Description:** Implement a function that compresses a string by counting the number of consecutive characters. Return the original string if the compressed string isn't shorter.
**Example:** `compressString("aabcccccaaa")` should return `"a2b1c5a3"`.
**Test/Mockup Data:** Use `"abcd"`, `"wwwwaaadexxxxxx"`.

### 3.5 Capitalize Words

**Description:** Create a function that takes a string and capitalizes the first letter of each word.
**Example:** `capitalizeWords("hello world")` should return `"Hello World"`.
**Test/Mockup Data:** Test with `"i am learning javascript"`, `"capitalize each word"`.

## 4 **Physics and Mathematics:**

### 4.1 Basic Projectile Motion Calculator

**Description:** Write a function that calculates the maximum height reached by a projectile given its initial velocity and angle of projection.
**Example:** `projectileHeight(30, 45)` should return the maximum height (in meters, assuming Earth's gravity).
**Test/Mockup Data:** Test with `(20, 30)`, `(40, 60)`.

### 4.2 Pythagorean Theorem Solver

**Description:** Create a function that solves for the hypotenuse or a leg of a right triangle, given the other two sides.
**Example:** `pythagoreanSolve('leg', 3, 4)` should return `5` (for hypotenuse).
**Test/Mockup Data:** Use `('hypotenuse', 5, 3)`, `('leg', 7, 24)`.

### 4.3 Simple Harmonic Motion Period Calculator

**Description:** Implement a function to calculate the period of simple harmonic motion given the mass and spring constant.
**Example:** `shmPeriod(2, 20)` should return the period of oscillation.
**Test/Mockup Data:** Test with `(1, 10)`, `(0.5, 30)`.

### 4.4 Compound Interest Calculator

**Description:** Write a function that calculates the future value of an investment given the principal amount, annual interest rate, and the number of years.
**Example:** `compoundInterest(1000, 5, 10)` should return the amount after 10 years.
**Test/Mockup Data:** Use `(2000, 3, 5)`, `(500, 7, 20)`.

### 4.5 Conversion Between Degrees and Radians

**Description:** Create a function that converts an angle given in degrees to radians, and vice versa.
**Example:** `convertAngle(180, 'toRadians')` should return π radians.
**Test/Mockup Data:** Test with `(3.1416, 'toDegrees')`, `(45, 'toRadians')`.
  
## 5 **Game Elements:**

### 5.1 Random Treasure Generator

**Description:** Write a function that randomly generates a treasure item from a list of items.
**Example:** `generateTreasure(['gold', 'silver', 'diamonds'])` should return one of the items randomly.
**Test/Mockup Data:** Use item lists like `['sword', 'shield', 'potion']`, `['ruby', 'emerald', 'sapphire']`.

### 5.2 Dice Roll Simulator

**Description:** Create a function that simulates the roll of a dice with a given number of sides.
**Example:** `rollDice(6)` should return a random number between 1 and 6.
**Test/Mockup Data:** Test with `4`, `20` (for four-sided and twenty-sided dice).

### 5.3 Scoring System for a Quiz Game

**Description:** Implement a function that calculates the total score for a quiz game, where each correct answer gives a certain number of points.
**Example:** `calculateScore(['correct', 'wrong', 'correct'], 10)` should return `20`.
**Test/Mockup Data:** Use answer arrays like `['correct', 'correct', 'correct']`, `['wrong', 'wrong']`.

### 5.4 Rock-Paper-Scissors Game

**Description:** Write a function that takes two inputs (choices of 'rock', 'paper', or 'scissors') and returns the winner.
**Example:** `rockPaperScissors('rock', 'scissors')` should return `'Player 1 wins'`.
**Test/Mockup Data:** Test with `('paper', 'rock')`, `('scissors', 'scissors')`.

### 5.5 Basic Enemy AI Behavior

**Description:** Create a function that determines an enemy's action (e.g., 'attack', 'defend', 'flee') based on its health percentage.
**Example:** `enemyAI(30)` (where 30 is the health percentage) might return 'flee'.
**Test/Mockup Data:** Use health values like `80`, `50`, `20`.

## 6 **Data Formatting and Validation:**

### 6.1 Currency Formatter

**Description:** Write a function that formats a number as a currency string (e.g., converting 123 to "$123.00").
**Example:** `formatCurrency(1234)` should return `"$1,234.00"`.
**Test/Mockup Data:** Test with`56`,`7890.5`.

### 6.2 Date Formatter

**Description:** Create a function that takes a date object and returns it in a readable format (e.g., "MM/DD/YYYY").
**Example:** `formatDate(new Date("2024-03-15"))` should return `"03/15/2024"`.
**Test/Mockup Data:** Test with `new Date("2024-12-01")`, `new Date("2024-07-04")`.

### 6.3 Email Validator

**Description:** Implement a function that validates an email address format.
**Example:** `validateEmail("example@email.com")` should return `true`.
**Test/Mockup Data:** Use `"plainaddress"`, `"@missingdomain.com"`, `"@domain.com"`.

### 6.4 Phone Number Formatter

**Description:** Write a function that takes a string of numbers and formats it into a standard phone number format (e.g., "(123) 456-7890").
**Example:** `formatPhoneNumber("1234567890")` should return `"(123) 456-7890"`.
**Test/Mockup Data:** Test with `"9876543210"`, `"1231231234"`.

### 6.5 Credit Card Masking

**Description:** Create a function that masks all but the last four digits of a credit card number with `'*'` and returns the masked string.
**Example:** `maskCreditCard("1234567890123456")` should return `"************3456"`.
**Test/Mockup Data:** Use `"5555444433332222"`, `"9876987698769876"`.

## 7 **DOM Manipulation (for Web Development):**

### 7.1 Dynamic Content Loader

**Description:** Write a function that dynamically loads content into a div element on a button click.
**Example:** Clicking a 'Load More' button should append new content to a div.
**Test/Mockup Data:** Use mock text or HTML elements for content.

### 7.2 Theme Toggler

**Description:** Create a function to toggle between light and dark themes on a webpage.
**Example:** Clicking a switch should change the background and text color of the page.
**Test/Mockup Data:** Set initial theme and provide a toggle element.

### 7.3 Form Validator

**Description:** Implement a function that validates input fields in a form when submitted.
**Example:** Check if email is valid and password field is not empty on form submission.
**Test/Mockup Data:** Use a simple form with email and password fields.

### 7.4 Image Carousel

**Description:** Write a function to create a basic image carousel with next and previous buttons.
**Example:** Clicking 'Next' or 'Previous' should change the displayed image.
**Test/Mockup Data:** Use an array of image URLs for the carousel.

### 7.5 Interactive Search Filter

**Description:** Create a function that filters and displays items from a list based on user input in a search bar.
**Example:** Typing in the search bar should filter the displayed list items in real-time.
**Test/Mockup Data:** Use a predefined list of strings or objects.

## 8 **Algorithm Challenges:**

### 8.1 Binary Search Implementation

**Description:** Implement the binary search algorithm to find a target value in a sorted array.
**Example:** `binarySearch([1, 2, 3, 4, 5], 3)` should return the index of `3`.
**Test/Mockup Data:** Test with sorted arrays and various target values.

### 8.2 Bubble Sort Algorithm

**Description:** Write a function that sorts an array of numbers using the bubble sort algorithm.
**Example:** `bubbleSort([3, 1, 4, 1, 5, 9, 2, 6])` should return a sorted array.
**Test/Mockup Data:** Use different unsorted arrays.

### 8.3 Palindrome Checker

**Description:** Create a function to check if a given string is a palindrome (ignoring spaces, punctuation, and case).
**Example:** `isPalindrome("A man, a plan, a canal, Panama")` should return `true`.
**Test/Mockup Data:** Test with various strings.

### 8.4 Fibonacci Sequence Generator

**Description:** Implement a function that returns the first `n` numbers of the Fibonacci sequence.
**Example:** `fibonacci(5)` should return `[0, 1, 1, 2, 3]`.
**Test/Mockup Data:** Test with different values of `n`.

### 8.5 Anagram Solver

**Description:** Write a function that checks if two strings are anagrams of each other.
**Example:** `isAnagram("listen", "silent")` should return `true`.
**Test/Mockup Data:** Use string pairs like `("binary", "brainy")`, `("restful", "fluster")`.

## 9 **Functional Programming:**

### 9.1 Currying Function

**Description:** Implement a function that transforms a function with multiple arguments into a sequence of nesting functions.
**Example:** `curryFunction(a, b, c)` should transform into `curryFunction(a)(b)(c)`.
**Test/Mockup Data:** Use a basic function like summing three numbers.

### 9.2 Implement `map` Function

**Description:** Create a custom `map` function that applies a given function to each item in an array and returns a new array.
**Example:** `customMap([1, 2, 3], x => x * 2)` should return `[2, 4, 6]`.
**Test/Mockup Data:** Test with various arrays and functions.

### 9.3 Recursive `reduce` Function

**Description:** Write a recursive version of the `reduce` function to accumulate array values based on a function.
**Example:** `recursiveReduce([1, 2, 3, 4], (acc, val) => acc + val, 0)` should return `10`.
**Test/Mockup Data:** Use different arrays and accumulator functions.

### 9.4 Memoization Function

**Description:** Implement a memoization function that caches the results of expensive function calls and returns the cached result when the same inputs occur again.
**Example:** `memoizedFibonacci(n)` should compute the Fibonacci number for `n` and cache it for future calls.
**Test/Mockup Data:** Test with `memoizedFibonacci(10)`, `memoizedFibonacci(10)` (second call should retrieve from cache).

### 9.5 Higher-Order Function for Logging

**Description:** Create a higher-order function that takes a function as an argument, logs the function's name and arguments, executes it, and then logs the result.
**Example:** `logFunctionExecution(Math.max, 1, 2, 3)` should log `"Executing max with arguments 1, 2, 3. Result: 3"`.
**Test/Mockup Data:** Use with different functions and arguments.

## 10 **Asynchronous Programming:**

### 10.1 Promise-Based Timeout Function

**Description:** Write a function that returns a promise which resolves after a given number of milliseconds.
**Example:** `delay(1000)` should return a promise that resolves after 1000 milliseconds.
**Test/Mockup Data:** Test with various time delays.

### 10.2 Asynchronous Data Fetch

**Description:** Create a function that fetches data from a URL and returns the data as a promise.
**Example:** `fetchData('https://api.example.com/data')` should return a promise with the fetched data.
**Test/Mockup Data:** Use any public API or mock API endpoint.

### 10.3 Promise.all() Implementation

**Description:** Implement a function that takes an array of promises and returns a promise that resolves when all of the promises resolve, similar to `Promise.all()`.
**Example:** `customPromiseAll([Promise.resolve(1), Promise.resolve(2)])` should resolve with `[1, 2]`.
**Test/Mockup Data:** Test with arrays of various resolved and rejected promises.

### 10.4 Sequential Promise Execution

**Description:** Write a function that executes an array of asynchronous functions in sequence (one after the other).
**Example:** `executeSequentially([asyncFunc1, asyncFunc2])` should ensure `asyncFunc2` runs after `asyncFunc1` completes.
**Test/Mockup Data:** Use mock asynchronous functions that log messages or return values.

### 10.5 Async/Await Error Handling

**Description:** Implement a function using async/await that fetches data from a URL and uses try/catch for error handling.
**Example:** `fetchWithAsyncAwait('https://api.example.com/data')` should handle errors gracefully.
**Test/Mockup Data:** Test with valid URLs and URLs that will cause an error (e.g., due to network issues or bad endpoints).


## 11 **Random:**

### 11.1 The Color Mixer

**Description:** Create a function that takes two strings representing colors in RGB format (e.g., "255,0,0" for red) and returns a new color that is the average of the two.
**Example:** mixColors("255,0,0", "0,0,255") should return "127,0,127".
**Test/Mockup Data:** Test with combinations like ("255,255,0", "0,255,255"), ("128,128,128", "128,128,128").

### 11.2 Array Sum Checker

**Description:** Write a function that takes an array of numbers and a target sum. It should return `true` if any two numbers in the array add up to the target sum, otherwise return `false`.
**Example:** `hasPairWithSum([1, 2, 3, 4], 5)` should return `true` (because 1 + 4 = 5).
**Test/Mockup Data:** Test with arrays like `[10, 15, 3, 7]` and target sum `17`, `[4, 5, 1, 8]` and target sum `2`.

### 11.3 String Reverser

**Description:** Create a function that takes a string and returns its reverse without using built-in `reverse` methods.
**Example:** `reverseString("hello")` should return `"olleh"`.
**Test/Mockup Data:** Test with strings like `"world"`, `"JavaScript"`.

### 11.4 Unique Character Finder

**Description:** Develop a function that takes a string and returns the first non-repeating character. If all characters repeat, return `null`.
**Example:** `firstUniqueChar("abacabad")` should return `'c'`.
**Test/Mockup Data:** Use strings like `"abba"`, `"aabbcc"`.

### 11.5 Factorial Calculator

**Description:** Write a function that calculates the factorial of a given number. The function should be able to handle numbers up to 20.
**Example:** `factorial(5)` should return `120`.
**Test/Mockup Data:** Test with numbers like `4`, `10`, `15`.
