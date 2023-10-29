# Initial Setup

## Introduction

In this section, we'll cover the initial tools you'll need to start front-end development.

### Visual Studio Code

Code editors are essential tools for every developer. They allow you to modify source code in various programming languages and provide functions to simplify work and enhance efficiency.

It's important to differentiate between code editors and **IDEs** (_Integrated Development Environments_). Editors for web development are generally lightweight programs or online platforms that offer everything you need for an effective and productive development experience, without unnecessary complexities. However, you can also use an **IDE** for web development.

Modern editors can expand their functionality through plugins, potentially making them as comprehensive as an **IDE**.

There are numerous code editors in the programming field, giving you the freedom to choose the one that suits you best. If you're unsure or lack knowledge in this area, let me introduce you to an excellent option. In this section, we'll discuss **Visual Studio Code**, known for its user-friendliness and wide range of functionalities. Other noteworthy editors include **Sublime Text** and **Vim**. However, note that **Sublime Text** is a paid option, and while **Vim** may have a steep learning curve initially, once mastered, it can significantly increase typing speed.

### Markdown

**Markdown** is a lightweight markup language developed by John Gruber in 2004. Its primary goal is to ensure optimal readability and easy publication. Inspired by existing conventions for marking email messages in plain text, **Markdown** allows you to apply formatting and styles through special characters in a simple and effective manner.

While this section is optional, it proves very useful as it enables you to write notes in an organized and appealing way. Additionally, it supports **HTML** code, allowing you to insert and interpret code.

### Terminal

The Terminal, often referred to as the console, is the user interface for command-line operations. It's a screen, typically with a black background and white text, where we input commands (special sequences of words) to instruct the system to perform specific actions. In this guide, I'll focus on teaching you the **Bash** terminal language, which is highly similar to the one used in **Linux** and also found in **macOS**.

## Tutorial

### Visual Studio Code

Here's an introduction to **Visual Studio Code**:

-   **[Learn Visual Studio Code - Course for Beginners](https://www.youtube.com/watch?v=yjeHLSrhPao)**

Additionally, here's some extra content about **Visual Studio Code**:

-   **[Live Server Extension for Visual Studio Code | Full Tutorial](https://www.youtube.com/watch?v=_Tl-6HeV0Rc)**
-   **[25 VS Code Productivity Tips and Speed Hacks](https://www.youtube.com/watch?v=ifTF3ags0XI)**

### Markdown

-   **[Markdown Tips & Tricks 2022 - Markdown Crash Course](https://www.youtube.com/watch?v=ftOBvusMHjQ)**

### Terminal

-   **[How to Install Git Bash on Windows 10](https://www.youtube.com/watch?v=qdwWe9COT9k)**

-   **[Command Line for Beginners – How to Use the Terminal Like a Pro [Full Handbook]](https://tutorials.codebar.io/command-line/introduction/tutorial.html)**

-   **[Beginner's Guide to the Bash Terminal](https://www.youtube.com/watch?v=oxuRxtrO2Ag)**

## Resources

-   Here are the keyboard shortcuts for **Visual Studio Code**:

    -   **[VSCode Shortcuts for Windows](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf)**
    -   **[VSCode Shortcuts for macOS](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf)**

-   Here is the official **[Markdown documentation](https://www.markdownguide.org)**. These are the sections of interest:

-   **[Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)**
-   **[Basic Syntax](https://www.markdownguide.org/basic-syntax/)**
-   **[Extended Syntax](https://www.markdownguide.org/extended-syntax/)**.

-   I've created a concise guide of **Bash** commands for you: **[Terminal Guide](../assets/Bash-en.md)**

## Tips, Tricks, and Best Practices

-   Here's a summarized table of very useful keyboard shortcuts that will optimize the usage of **Visual Studio Code**:

    | Shortcut                              | Action                                      |
    | ------------------------------------- | ------------------------------------------- |
    | Alt + Shift + A                       | Convert selection to a comment              |
    | Alt + Click                           | Make multiple selections                    |
    | Alt + Shift + Up/Down                 | Duplicate lines                             |
    | Alt + Up/Down                         | Move lines up or down                       |
    | Alt + Z                               | Toggle "Word Wrap"                          |
    | Ctrl + ,                              | Open settings menu                          |
    | Ctrl + .                              | Open context menu                           |
    | Ctrl + /                              | Convert line to comment                     |
    | Ctrl + D                              | Select current word                         |
    | Ctrl + D, Ctrl + D (Multiple times)   | Select and edit next occurrence             |
    | Ctrl + F                              | Search                                      |
    | Ctrl + F4 (Ctrl + W)                  | Close current file                          |
    | Ctrl + H                              | Search and replace                          |
    | Ctrl + K + P (Ctrl + Tab)             | Select open file                            |
    | Ctrl + K + W                          | Close all open files                        |
    | Ctrl + P                              | Select file in opened directory             |
    | Ctrl + Right/Left                     | Move between words                          |
    | Ctrl + S                              | Save current file                           |
    | Ctrl + Shift + P                      | Execute command from **Visual Studio Code** |
    | Ctrl + Space                          | Activate suggestions (Intellisense)         |
    | Ctrl + X                              | Cut current line                            |
    | Ctrl + Y                              | Undo last undone action                     |
    | Ctrl + Z                              | Undo last action                            |
    | Ctrl + ` (or Ctrl + J)                | Open terminal                               |
    | Del                                   | Delete next character                       |
    | End                                   | Go to end of line                           |
    | Home                                  | Go to beginning of line                     |
    | Tab (Selection + Tab)                 | Increase indentation                        |
    | Shift + Tab (Selection + Shift + Tab) | Decrease indentation                        |

-   To create personalized keyboard shortcuts for **Visual Studio Code**, follow these steps:

    1. Go to preferences via the "File" menu, select "Preferences," and then "Keyboard Shortcuts." Alternatively, use the shortcut `Ctrl + K Ctrl + S`.
    2. Search for the command you want to create a shortcut for. Edit existing shortcuts or create a new one by clicking the "+" symbol at the top.
    3. Define the key combination for your personalized shortcut, using `Ctrl`, `Shift`, and `Alt` in combination with other keys. Ensure there are no conflicts with existing keyboard shortcuts.
    4. Save the modifications to the keyboard shortcuts file. Test the new shortcut to verify its expected behavior.

-   In programming, a "Snippet" refers to a small, reusable piece of source code, binary code, or text. There are predefined snippets for almost every technology created by the community, which you can find in the extensions section. To create a snippet, press `Ctrl + Shift + P`, then select `Snippets: Configure User Snippets` and start writing the snippet in the desired language. You'll find a brief explanation of how to do it there.

-   Extensions can significantly optimize the development process. Here are some that will aid you in web development:

    -   **[Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)** is an extension that allows you to load any web page and apply changes in real-time. It's an essential tool for web development.

    -   **[Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)** facilitates the process of changing the name of tags. If you modify the opening tag name, it will automatically change the closing tag name.

    -   **[Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)** allows you to see syntax errors directly on the line, making it easier to identify errors.

    -   **[Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)** formats your code after every save, so you won't have to worry about writing more organized code.

## Conclusion

With this, you now possess the knowledge and tools to start practicing code writing and significantly improve your programming speed.
