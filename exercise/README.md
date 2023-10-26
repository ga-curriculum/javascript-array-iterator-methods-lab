# ![tktk Module Name - Lab Exercise](./assets/hero.png)

## Introduction

This lab provides an opportunity to practice working with array iterator methods in JavaScript.

### A quick note before you dive in

If you find yourself stuck during the lab, we encourage you to first revisit the lesson materials. They're designed to provide you with the information and examples that will help you complete the exercises. 

If you've revisited the materials and are still facing challenges, don't hesitate to collaborate with your classmates.

Lastly, the internet is filled with resources specific to JavaScript arrays. Websites like [Google](https://www.google.com/), [MDN Web Docs on Array Iterator Methods](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array#iterative_methods), and [Stack Overflow](https://stackoverflow.com/search?q=javascript+array+iterator+methods) are just a few clicks away. Use these as a last resort, before reaching out for help.

Happy coding!

## Data Setup

Copy and paste each of the following arrays at the top of our `script.js` file to serve as our `database` which we will use to practice our array iterator methods.

### Inventors

```js
const inventors = [
  { first: 'Albert', last: 'Einstein', year: 1879, passed: 1955 },
  { first: 'Isaac', last: 'Newton', year: 1643, passed: 1727 },
  { first: 'Galileo', last: 'Galilei', year: 1564, passed: 1642 },
  { first: 'Marie', last: 'Curie', year: 1867, passed: 1934 },
  { first: 'Johannes', last: 'Kepler', year: 1571, passed: 1630 },
  { first: 'Nicolaus', last: 'Copernicus', year: 1473, passed: 1543 },
  { first: 'Max', last: 'Planck', year: 1858, passed: 1947 },
  { first: 'Katherine', last: 'Blodgett', year: 1898, passed: 1979 },
  { first: 'Ada', last: 'Lovelace', year: 1815, passed: 1852 },
  { first: 'Sarah E.', last: 'Goode', year: 1855, passed: 1905 },
  { first: 'Lise', last: 'Meitner', year: 1878, passed: 1968 },
  { first: 'Hanna', last: 'Hammarström', year: 1829, passed: 1909 }
];
```

### People

```js
const people = [
  'Becker, Carl', 'Beckett, Samuel', 'Beddoes, Mick', 'Beecher, Henry',
  'Beethoven, Ludwig', 'Begin, Menachem', 'Belloc, Hilaire', 'Bellow, Saul',
  'Benchley, Robert', 'Benenson, Peter', 'Ben-Gurion, David',
  'Benjamin, Walter', 'Benn, Tony', 'Bennington, Chester', 'Benson, Leana',
  'Bent, Silas', 'Bentsen, Lloyd', 'Berger, Ric', 'Bergman, Ingmar',
  'Berio, Luciano', 'Berle, Milton', 'Berlin, Irving', 'Berne, Eric',
  'Bernhard, Sandra', 'Berra, Yogi', 'Berry, Halle', 'Berry, Wendell',
  'Bethea, Erin', 'Bevan, Aneurin', 'Bevel, Ken', 'Biden, Joseph',
  'Bierce, Ambrose', 'Biko, Steve', 'Billings, Josh', 'Biondo, Frank',
  'Birrell, Augustine', 'Black, Elk', 'Blair, Robert', 'Blair, Tony',
  'Blake, William'
];
```

### Travel Methods

```js
const travelMethods = [
  'car', 'car', 'truck', 'truck', 'bike', 'walk', 'car', 'van',
  'bike', 'walk', 'car', 'van', 'car', 'truck'
];
```

### Devs

```js
const devs = [
  { name: 'Wes', year: 1988 },
  { name: 'Kait', year: 1986 },
  { name: 'Irv', year: 1970 },
  { name: 'Lux', year: 2015 }
];
```

### Comments

```js
const comments = [
  { text: 'Love this!', id: 523423 },
  { text: 'Super good', id: 823423 },
  { text: 'You are the best', id: 2039842 },
  { text: 'Ramen is my fav food ever', id: 123523 },
  { text: 'Nice Nice Nice!', id: 542328 }
];
```

## Lab Exercises

Copy and paste each of the following exercises into your JavaScript file. To check your work, open the file in a web browser and inspect the console output, or run the file in your terminal using `node script.js`.

### Exercise 1: Array.prototype.filter()

```js
// Array.prototype.filter()

// 1. Filter the array of inventors into a new array containing only the inventors born in the 1500's
```

### Exercise 2: Array.prototype.map()

```js
// Array.prototype.map()

// 2. Map the array of the inventors into a new array containing objects with just the first and last names as properties

// Hint:  Return a new object literal from the callback (don't mutate the object being passed in to map)
```


### Exercise 3: Array.prototype.sort()

```js
// Array.prototype.sort()

// 3. Sort the inventors by birth date (year property), in ascending order
```

### Exercise 4: Array.prototype.find()

```js
// Array.prototype.find()

// 4. Find the inventor object with the first name of 'Ada'
```

### Exercise 5: Array.prototype.map()

```js
// Array.prototype.map()

// 5. Map the people array such that the new array consists of strings with the names formatted as "First Last", e.g., "Becker, Carl" should be mapped to "Carl Becker".

// Hint: As a start, consider using the String.prototype.split method to "split" the string using ', ' as the separator
```

### Exercise 6: Array.prototype.some()

```js
// Array.prototype.some()

// 6. Check if at least one person is 19 or older?

// Hint: To get today's year, use the getFullYear method of new Date(), i.e., new Date().getFullYear()
```

### Exercise 7: Array.prototype.every()

```js
// Array.prototype.every()

// 7. Check if everyone is 19 or older?
```

### Exercise 8: Array.prototype.find()

```js
// Array.prototype.find()

// 8. Find the comment with the id of 823423
```

### Exercise 9: Array.prototype.findIndex()

```js
// Array.prototype.findIndex()

// 11. Find the index of the comment with an id of 123523
```

🎉 The End. You did it! 🎉

## Bonus Exercises: Array.prototype.reduce()

Try the following exercises if you completed the `Level Up` section of the Array Iterator Methods lesson on `.reduce()`

### Bonus Exercise 1:

```js
// Array.prototype.reduce()

// Bonus 1. How many years did all the inventors live?
```

### Bonus Exercise 2:

```js
// Array.prototype.reduce()

// Bonus 2. Count the number of instances for each of the data items. The reduce should return an object where the keys are 'car', 'truck', etc. and the values are the count.

// Hint: Since you want to return an object, be sure to pass an empty {} for the initial value of the "accumulator".
```

🌟 With the BONUS! Amazing! 🌟
