# HTML

## Introduction

**HTML** (_HyperText Markup Language_) is the markup language used to create websites. It's a standard language for defining the structure and content of a web page, including text, images, videos, forms, and more.

Currently, it's in its fifth version (**HTML5**), which has introduced a host of new features compared to the early days of the internet.

We'll also delve into **Emmet**. This handy extension for code editors accelerates the process of writing and editing various formats like **HTML**, **XML**, **XSL**, and more. Through content assistance, **Emmet** enables quick and efficient editing of **HTML** and **CSS** code using abbreviations.

For website developers dealing with **HTML** files, a basic editor might not suffice. Especially for Front-end development, **Emmet** plays a crucial role in boosting productivity. This plugin employs short abbreviations to generate extensive **HTML** and **CSS** code structures, allowing for the swift creation of complex content. Although optional, **Emmet** can significantly enhance productivity and efficiency when working with **HTML** and **CSS** code.

## Tutorial

### HTML

-   **[Learn HTML – Full Tutorial for Beginners (2022)](https://www.youtube.com/watch?v=kUMe1FH4CHE)**

### Emmet

-   **[Learn Emmet In 15 Minutes - Double Your HTML Coding Speed](https://www.youtube.com/watch?v=V8vizNQKtx0)**

## Resources

-   Discover a page that offers icons and images in **SVG** format for free: **https://www.svgrepo.com/**

-   Explore a website that presents a table of **HTML** tags, inspired by the periodic table of chemical elements: **https://madebymike.github.io/html5-periodic-table/**

-   Access a free and open-source **CDN** at **https://cdnjs.com/**. If you're unsure about what a **CDN** is, this videos explains it in a simple way:

-   **[What Is A CDN? How Does It Work?](https://www.youtube.com/watch?v=RI9np1LWzqw)**
-   **[How to Use Font Awesome Icon on HTML Website using CDN - Complete Tutorial](https://www.youtube.com/watch?v=ihTB-aZ-Msk)**

-   Here is the reference cheat sheet for **Emmet**: **[Emmet Cheat Sheet](https://docs.emmet.io/cheat-sheet/)**.

-   Dive into these websites that provide tips and best practices for **HTML** and **CSS**:
    -   **https://codeguide.co/**
    -   **https://webdesign.tutsplus.com/30-html-best-practices-for-beginners--net-4957t**

## Tips, Tricks, and Best Practices

-   When validating forms, don't rely only on the required attribute. Implement server-side validations for added security.

-   Place `<link>` tags in your `<head>` section, preferably towards the end. Similarly, put `<script>` tags in your `<body>` section, also towards the end.

    ```html
    <!DOCTYPE html>
    <html lang="en">
        <head>
            <meta charset="UTF-8" />
            <meta
                name="viewport"
                content="width=device-width, initial-scale=1.0"
            />
            <title>Document</title>
            <!-- CSS Styles -->
            <link rel="stylesheet" href="styles.css" />
        </head>
        <body>
            <!-- JavaScript Code -->
            <script src="index.js"></script>
        </body>
    </html>
    ```

-   If you use special characters like `<, >, &, "`, it's crucial to use specific shortcuts in your **HTML** code. This ensures they display correctly when using **JavaScript** or **PHP** code. Here are the expected shortcuts:
    | Shortcuts | Symbols |
    | ------------- | -------- |
    | `&lt;` | < |
    | `&gt;` | > |
    | `&amp;` | & |
    | `&quot;` | " |

-   To optimize performance, restrict the use of the `<iframe>` tag to a maximum of two per page.

-   For optimizing `<iframe>` tags from YouTube, you can use **https://tube.rvere.com/**. It loads the video only when clicked, improving page optimization. Replace the actual `<iframe>` code with the provided code.

-   In an **HTML** document, there should be only one `<h1>` element.

-   Avoid including styles or **JavaScript** code directly in your **HTML** content. Instead, write them in separate files for better organization.

-   Provide a relevant value for the `alt` attribute in your images. This improves accessibility and search engine rankings.

-   Include a canonical **URL** in the `<head>` section of your web page for improved search engine indexing:

    ```html
    <link rel="canonical" href="https://example.com/preferred-url-here/" />
    ```

-   Use `<em>` for emphasizing text rather than `<i>`. `<i>` is now widely accepted for representing icons.

-   To test your website on your phone, ensure it's connected to the same network as your computer. Type `ipconfig` in the terminal, find the **IPv4 Address**, and enter this IP address along with your server's port in your phone's browser. For example, `192.168.0.230:5500`. If this doesn't work, follow the instructions in this video: **https://www.youtube.com/watch?v=uRYHX4EwYYA**.

-   Favicon functionality is limited to desktop browsers and not mobile devices. To enable favicons on mobile websites, add this additional tag to your `<head>` section: `<link rel="apple-touch-icon" href="img/favicon.png">`.

-   In general, it's preferred to use images in **SVG** or **WEBP** formats on your website instead of **PNG** or **JPG**. For an in-depth explanation, refer to this article: **https://ed.team/blog/que-imagenes-debes-usar-en-tu-web-jpg-png-svg-o-webp**

-   Avoid excessive use of `<div>` tags. Instead, opt for semantic tags like `<main>`, `<section>`, `<article>`, and others for cleaner and more structured code:

    ```html
    <!-- BAD -->
    <div>
        <div>
            <div>
                <p>Lorem ipsum dolor sit amet.</p>
            </div>
        </div>
    </div>

    <!-- GOOD -->
    <article>
        <section>
            <div>
                <p>Lorem ipsum dolor sit amet.</p>
            </div>
        </section>
    </article>
    ```

-   Always include the language tag `<lang>` in the `<html>` tag. This helps voice synthesis tools determine appropriate pronunciations and translation tools apply correct grammatical rules.

-   The `<title>` tag is recommended to have between 55 and 65 characters, while the `<meta name="description">` tag should not exceed 165 characters for optimal page positioning.

-   For better code readability, follow this attribute order for **HTML** elements:

    1. class
    2. id, name
    3. data-
    4. src, for, type, href, value
    5. title, alt
    6. role, aria-
    7. tabindex
    8. style

-   Use the attribute `tabindex="0"` to create interactive elements that can be navigated with the Tab key without changing the order of the tabulation.

-   A boolean attribute is one that doesn't require a declared value. While **XHTML** demands a value declaration, **HTML5** does not.

## Exercises and Projects

Typically, exercises that involve both **HTML** and **CSS** are used for practice. However, here's a simple exercise to start with: **[Learn HTML by Building a Cat Photo App - FreeCodeCamp](https://www.freecodecamp.org/learn/2022/responsive-web-design/#learn-html-by-building-a-cat-photo-app)**.

## Conclusion

That covers the basics of **HTML**. There are two more essential building blocks in web programming: **CSS** and **JavaScript**. You'll learn how to use them in their respective sections.
