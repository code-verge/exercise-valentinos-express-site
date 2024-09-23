# exercise-valentinos-express-site

## Learning Goals

Upon completing this exercise, you will be able to:

- A
- B

## Introduction



## Getting Started

1. Fork the repository
2. Clone the repository to your computer
3. Open the repository in VS Code
4. Start the Live Server in VS Code
5. Follow instructions

## **Instructions**


## **Submission**

When you've completed the exercise:

1. Run the following commands:

```jsx
git add .
git commit -m "Completed Valentinos Express Site"
git push origin main
```

1. Create a Pull Request and submit your assignment.

Happy coding, agent! 🕵🏻‍♀️💻

## Frequently Asked Questions (FAQs)

<details>
  <summary>How can I iterate over an array in JavaScript?</summary>
 
You can use a `for` loop or the `forEach()` method to iterate over an array in JavaScript. The `for` loop allows you to specify the starting point, condition, and increment/decrement, while the `forEach()` method executes a provided function once for each array element.
    
    ```jsx
    // for loop
    const numbers = [1, 2, 3, 4, 5];
    for (let i = 0; i < numbers.length; i++) {
      console.log(numbers[i]);
    }
    
    // forEach method
    const numbers = [1, 2, 3, 4, 5];
    numbers.forEach(function(number) {
      console.log(number);
    });
    ``` 
 
</details>

<details>
  <summary>How can I create an object in JavaScript?</summary>
 
You can create an object in JavaScript using the object literal notation. Object literal notation is the most common way, where you define an object using curly braces `{}` and specify its properties and values using key-value pairs.
    
    ```jsx
    // Creating an object using object literal notation
    const person = {
      name: "John",
      age: 30,
      city: "New York"
    };
    ```

 
</details>

<details>
  <summary>What is the `map()` method in JavaScript?</summary>
 
The `map()` method creates a new array by calling a provided function on every element in the original array. It transforms each element based on the logic defined in the provided function and returns a new array with the transformed elements.
    
    ```jsx
    const numbers = [1, 2, 3, 4, 5];
    const doubledNumbers = numbers.map(function(number) {
      return number * 2;
    });
    console.log(doubledNumbers); // Output: [2, 4, 6, 8, 10]
    ```
 
</details>

<details>
  <summary>How can I filter an array based on a specific condition?</summary>

You can use the `filter()` method to create a new array with all elements that pass a specific condition. The `filter()` method takes a callback function as an argument, which is executed for each element in the array. The elements for which the callback function returns true are included in the new array.
    
    ```jsx
    const numbers = [1, 2, 3, 4, 5];
    const evenNumbers = numbers.filter(function(number) {
      return number % 2 === 0;
    });
