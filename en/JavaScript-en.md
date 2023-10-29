# JavaScript

## Introduction

**JavaScript** is a versatile programming language that empowers the creation of dynamic functions within web pages. When a website goes beyond displaying static information and starts offering timely updates, interactive maps, 2D/3D animations, video playback with motion, and more, it's highly likely that **JavaScript** is behind this interactivity. This language constitutes the third layer in a standard set of web technologies, complementing the previous two (**HTML** and **CSS**), which we explored in their respective sections.

While **HTML** defines a website's structure and **CSS** arranges and styles that structure, neither of these languages is geared towards traditional programming. Conventional programming languages, on the other hand, enable the use of variables, functions, loops, and conditional structures, just like **JavaScript**.

**JavaScript** boasts a wide range of applications and tools, making it one of the most popular and beloved languages within the development community. However, it does attract some criticism due to certain distinctive aspects. These differences become more noticeable as you gain experience in other programming languages. I suggest that after mastering **JavaScript**, you consider learning other languages like **Python**, **C#**, **Java**, among others. This will broaden your understanding of the programming world and allow you to discern the similarities and differences between various languages.

In my personal experience, expanding my knowledge to other languages, such as **Python** and **C#**, after having programmed with **JavaScript**, provided a fresh perspective and enriched my understanding of programming. However, it's important to note that trying to master too many languages can lead to confusion and a lack of proficiency, hindering your progress. Therefore, it's advisable to focus on one or two languages that you deeply master, and have a basic knowledge of others. This will enable you to concentrate on the languages that truly matter for your projects and goals.

Additionally, it's worth mentioning that **JavaScript** isn't limited to front-end development. It's also used in back-end development through **Node.js**, which allows you to execute **JavaScript** code on the server side. **Node.js** compiles **JavaScript** code so that machines can read it. While primarily associated with back-end development, certain specifications, such as the package manager **npm**, are also applied in front-end development.

You now have the opportunity to delve into learning this language and its applications through the resources provided below. These resources will guide you in understanding how to use **JavaScript** effectively.

## Tutorial

-   **[Modern JavaScript From The Beginning | First 12 Hours](https://www.youtube.com/watch?v=BI1o2H9z9fo)**
-   **[Full HTTP Networking Course – Fetch and REST APIs in JavaScript](https://www.youtube.com/watch?v=2JYT5f2isg4)**

## Resources

-   Websites offering tips and best practices for **JavaScript**:
    -   **https://code.tutsplus.com/es/24-javascript-best-practices-for-beginners--net-5399t**
    -   **https://github.com/airbnb/javascript**

## Tips, Tricks, and Best Practices

-   Prefer using `===` over `==` because `===` checks both the value and data type, whereas `==` only checks the value. Here's an example:

    ```javascript
    let a = 3;

    console.log(a == 3); // Returns true
    console.log(a === 3); // Returns true

    console.log(a == "3"); // Returns true
    console.log(a === "3"); // Returns false
    ```

-   Avoid using `eval()` in your code as it can reduce performance and pose a security risk by granting excessive privileges to evaluated text.

-   Always use the `let` keyword instead of `var` when declaring variables. For a concise explanation, you can watch this video on YouTube: **[JavaScript Let vs Var vs Constant | Mosh](https://www.youtube.com/watch?v=XgSjoHgy3Rk)**.

-   Commenting code may seem unnecessary at first, but it's crucial. Imagine returning to your project after months and struggling to remember the purpose of each code fragment. Moreover, consider that another programmer may need to review your work; without comments, they could get lost. So, comments are very valuable.

-   While it's technically possible to omit semicolons in your code, it's not recommended. This can lead to issues and difficulties in the future. Therefore, continue using semicolons at the end of each line to ensure code clarity and correct interpretation.

-   While libraries and frameworks can ease application development, avoid excessive dependence on them. This can negatively impact performance and limit your programming ability. Use them judiciously, ensuring that you can accomplish what the library or framework offers on your own and that the impact is more positive than negative in your case.

-   It's better to use new array methods like `array.toSorted()` and `array.toReversed()` for array manipulation instead of `array.reverse()` or `array.sort()`. This is because new methods create a copy of the array, while the old ones modify the original array, potentially disrupting the original order.

-   To make copies of an array, the simplest method is to use the _Spread Operator_:

    ```js
    let arr = [1, 2, 3];
    let arrCopy = [...arr];

    arrCopy.push(4);

    // arr = [1, 2, 3]
    // arrCopy = [1, 2, 3, 4]
    ```

    However, this won't work for multidimensional arrays (arrays containing other arrays):

    ```js
    let arr = [[1, 2], [3]];
    let arrCopy = [...arr];

    arrCopy[1].push(4);

    // arr = [[1, 2], [3, 4]]
    // arrCopy = [[1, 2], [3, 4]]
    ```

    There are two simple ways to copy multidimensional arrays:

    1. Using the `slice()` method with `map()`:

        ```js
        let arr = [[1, 2], [3]];
        let arrCopy = arr.map((item) => item.slice());

        arrCopy[1].push(4);

        // arr = [[1, 2], [3]]
        // arrCopy = [[1, 2], [3, 4]]
        ```

    2. Converting to JSON and back to JavaScript:

        ```js
        let arr = [[1, 2], [3]];
        let arrCopy = JSON.parse(JSON.stringify(arr));

        arrCopy[1].push(4);

        // arr = [[1, 2], [3]]
        // arrCopy = [[1, 2], [3, 4]]
        ```

    For more information about this behavior, check out this article: **[Deep Copying JavaScript Arrays](https://medium.com/@ziyoshams/deep-copying-javascript-arrays-4d5fc45a6e3e)**

-   You can swap the values of two variables using destructuring:

    ```js
    let a = 8;
    let b = 6;

    [a, b] = [b, a];

    // a = 6
    // b = 8
    ```

-   You can create loops using recursion, which is a more complex and efficient way to iterate. To apply recursion, you must create a function that calls itself within and that has a condition that stops the recursive calling at the beginning of the function. Since it's a complicated topic, here are some resources to learn more about it: **[What Is Recursion - In Depth](https://www.youtube.com/watch?v=6oDQaB2one8)**.

-   Regular expressions are fundamental for finding words or terms in any text. However, using them can be tedious, and it's easy to forget them if you don't use them often. That's why I'm providing you with a reference syntax sheet of regular expressions and exercises from FreeCodeCamp for practice purposes:

    -   **[Regular Expressions Syntax Reference Sheet](https://developer.mozilla.org/es/docs/Web/JavaScript/Guide/Regular_expressions/Cheatsheet)**
    -   **[Exercises with Regular Expressions - FreeCodeCamp](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#regular-expressions)**

## Exercises and Projects

-   **[Exercism](https://exercism.org)** is an excellent platform for developing and honing your programming efficiency and logic in various languages. They offer over 140 programming exercises in the **JavaScript** section.

-   **[JavaScript Algorithms and Data Structures - FreeCodeCamp](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/)** provides a course with practical exercises and offers a widely recognized certification.

## Conclusion

And here we conclude our exploration of **JavaScript**. With the acquisition of these three fundamental pillars of web programming, you're now equipped to build a website using just these three languages. The next step will be to delve into technologies, libraries, and tools that will significantly enhance your development capabilities and expand your job prospects, provided you have the necessary knowledge and experience in this field.

However, entering the job market without knowledge of these technologies is nearly impossible. If your goal is to secure a job, learning and mastering these will be an essential requirement. On the other hand, if it's for personal development, they remain more optional.
