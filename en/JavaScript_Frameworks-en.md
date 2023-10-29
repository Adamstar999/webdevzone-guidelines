# JavaScript Frameworks

## Introduction

Frameworks have been in existence for decades. They are essentially sets of pre-written code designed to streamline the development of specific functions or projects.

For instance, imagine implementing a feature where users can drag elements on the screen while holding down the mouse click, and the element remains in the position where the click was released. This function is commonly known as "_drag and drop_". While achievable with pure **JavaScript**, using a library can save time by not having to start from scratch.

There are more extensive and comprehensive libraries or frameworks that facilitate the creation of much more complex projects. Contemporary frameworks and libraries enable the optimization of web application development from start to finish, focusing on building **SPA** (Single Page Application) pages. These pages consist of a single web page that doesn't require visiting other **HTML** files or reloading the page, as all the content is located on one page and it's completely reactive.

Before the arrival of modern **JavaScript** libraries and frameworks for constructing **SPA** websites, such as **React**, **Vue**, and others, the predominant tool of that era was **jQuery**. This library facilitated interaction with **HTML** elements, allowing for style adjustments, cross-browser compatibility checks, and error reduction in **JavaScript** functions. During its time, **jQuery** was the go-to tool.

In contemporary projects, there's generally no need for **jQuery**, as all its functionalities are now covered by native **JavaScript**. However, many projects still use **jQuery**, often due to the substantial effort and cost it would take to transition to a newer framework or library, particularly in large projects. For independent developers or freelancers, learning **jQuery** may not be imperative at this point. However, in many companies, knowledge of **jQuery** is a prerequisite for certain positions, thereby expanding job opportunities. Mastering **jQuery** is relatively straightforward if you already have a grasp of **JavaScript**'s **DOM**.

We will cover **jQuery** here, but remember that it's entirely optional and not comparable to the other frameworks. It's more of an external library that could increase your chances of finding a job.

It's crucial to be mindful of excessive reliance on libraries and frameworks, as it can potentially slow down the application's performance due to the additional processing the browser has to handle. Moreover, having multiple libraries in your project can lead to compatibility issues that are challenging to resolve. In this section, our main focus will be on one particular framework, namely **React**, but we'll also touch on key aspects and resources of other frameworks.

## Tutorial

The list of frameworks and libraries is extensive and continues to expand each year. I'll mention three main frameworks: **React**, **Vue**, and **Angular**. We will focus mainly on **React**, and also mention **jQuery**. Although there are other frameworks, they are less commonly used and offer fewer job opportunities. However, if you want to use some of those, you are free to do so, as each has its advantages and disadvantages. Before delving into frameworks, I recommend watching this video that compares the differences between them, which will help you understand which one will be better for your needs: **[Angular vs React vs Vue: Which Framework to Learn in 2022](https://www.youtube.com/watch?v=T2uKprwHHXU)**

### jQuery

**jQuery** is an older library that doesn't offer anything new, but it is still widely used. Here are some guides if you want to learn it:

-   **[Learn jQuery for Beginners - Full Course](www.youtube.com/watch?v=ScoURsEM_yU)**
-   **[Official jQuery Documentation](https://api.jquery.com)**

### Angular

**Angular** is a framework based on components used to create scalable web applications, developed by Google. It offers a well-integrated collection of libraries that cover a wide variety of features, such as routing, form administration, client-server communication, and more. It also provides a set of tools for developers that facilitate the development, compilation, testing, and updating of the source code of your application. **Angular** is based on **TypeScript**, so it's important to be familiar with this language to work with **Angular**. Here are the resources to learn it:

-   **[Learn Angular A-Z: Complete Tutorial for Beginners](https://www.youtube.com/watch?v=JWhRMyyF7nc)**
-   **[Official Angular Documentation](https://angular.io/docs)**

### Vue

**Vue** is a progressive framework for building user interfaces. Unlike other monolithic frameworks, **Vue** is designed from scratch to be used incrementally. The central library is focused solely on the visual layer and is easy to use and integrate with other libraries or existing projects. **Vue** was created by Evan You, a former employee of Google, in 2014. Here are the resources to learn it:

-   **[Vue.js Tutorial: Beginner to Front-End Developer](https://www.youtube.com/watch?v=1GNsWa_EZdw)**
-   **[Official Vue Documentation](https://es.vuejs.org/v2/guide/)**

### React

**React** is one of the most popular **JavaScript** libraries for web and mobile application development. Created by Facebook, **React** has a collection of reusable **JavaScript** code fragments used to create user interfaces, called components.

It's important to clarify that **React** is not a **JavaScript** framework. This is because it is only responsible for rendering components in the visual layer of an application. **React** is an alternative to frameworks like **Angular** or **Vue**, which allow the creation of complex functions. Here are the resources to learn it:

-   **[React Course For Beginners - Learn React in 8 Hours](https://www.youtube.com/watch?v=f55qeKGgB_M)**
-   **[Official React Documentation](https://react.dev/learn)**

I'll also provide some supplementary videos about **React**, given its central importance.

-   **[Client-Side VS Server-Side Rendering - Data Fetching with Next.js](https://www.youtube.com/watch?v=f1rF9YKm1Ms)**
-   **[Beginner React.js Coding Interview (ft. Clément Mihailescu)](https://www.youtube.com/watch?v=gnkrDse9QKc)**
-   **[Do you REALLY need SSR?](https://www.youtube.com/watch?v=kUs-fH1k-aM)**

While I won't rule out the possibility of adding more content on other libraries or frameworks in the future, for now, we'll concentrate solely on **React**. However, if you prefer to explore other options, feel free to seek out online resources and use them, as they are all equally valid.

## Resources

-   This image illustrates an advisable way to organize the folders in your **React** projects:
    ![React Project Structure](../assets/React%20SRC.jpg)

## Tips, Tricks, and Best Practices

-   You can use the `HashRouter` component, especially if you have cases where URLs on your page encounter issues when accessed from another location. This is a common occurrence with shared hosting. Nevertheless, it's generally better to use `BrowserRouter`.

## Exercises and Projects

### Angular

-   **[Angular Projects](https://www.youtube.com/playlist?list=PLIjdNHWULhPQ2JUw3SX5mPCmjLGWmXqnu)**

### Vue

-   **[Vue Projects](https://www.youtube.com/playlist?list=PLA1RSE1qWuKClzNo6jVN6BMyVOWNR-ymd)**

### React

-   The **[JavaScript Mastery](https://www.youtube.com/@javascriptmastery)** YouTube channel offers a range of videos for daily project practice using the latest technologies.
-   **[FreeCodeCamp](https://www.freecodecamp.org/learn/2022/responsive-web-design/)** provides a course with practical exercises and offers a widely recognized certification.

## Conclusion

After becoming proficient with a framework or library and gaining ample practice, you'll not only be able to create a website with a complex and organized structure, but also possess the necessary knowledge to embark on a job search. There will be a section to guide you through the job search process and advise on what to include in your CV. We'll also cover topics more oriented towards design, such as **CSS** frameworks. However, in comparison to **JavaScript** frameworks and libraries, they are relatively straightforward.
