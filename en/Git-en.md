Git

## Introduction

When you're working on any application, it's crucial to have a backup. You've probably seen version numbers like _1.1_, _v1.3_, or _2.1.4_ in applications or video games, usually displayed in the corner. These numbers represent the available version of that program. Managing versions of an application is typically done using **Git**. **Git** provides you with nearly complete control over your code, allowing you to maintain a comprehensive version history and easily switch between them. It also streamlines collaboration within projects, making it easy to identify the person responsible for any errors in your application, among other things. So, in essence, **Git** is an indispensable tool for programming in any field.

Additionally, some platforms have emerged that allow you to visualize and store the files you've saved, providing a more convenient way to manage your repositories. These platforms include **GitHub**, **GitLab**, and **BitBucket**.

For this guide, we'll set aside **BitBucket** because it's less popular and has fewer options and functionalities. However, that doesn't mean it's a bad choice, it's just less commonly used. If you're interested, you can explore it on your own. Both **GitHub** and **GitLab** are excellent options, each with its own pros and cons. You'll find a video explaining the differences between them.

## Tutorial

<!-- Add the video tutorials --->

## Resources

<!-- Add the resources --->

## Tips, Tricks and Best Practices

-   If you'd like to switch the main branch to `main`, use this command: `git config --global init.defaultBranch main`. While the preference for `main` over `master` is subjective, it's widely accepted in professional settings.

-   To change the user on the current computer, execute these two commands:

    ```bash
    git config --global user.name "GithubUsername"
    git config --global user.email GithubEmail@gmail.com
    ```

-   Personally, the sequence I prefer from initialization to the first push to the repository looks like this:

    ```bash
    touch README.md
    touch .gitignore
    git init
    git add .
    git tag -a "App Version" -m "Tag Message"
    git commit -m "Commit message"
    git remote add origin https://github.com/user/repository.git
    git push --tags
    git push -u origin main
    ```

-   Use `git tag` to view the versions of your application.

-   Once you've pushed once, the next time you only need to write `git push` unless you want to push to another branch.

-   To push to a private repository, follow these steps:

    1. Go to your profile on **GitHub**, navigate to Settings > Developer settings > Personal Access Token > Tokens(classic).
    2. Generate a Token, set the expiration date, and be sure to copy the token and save it in a secure place, like a text file, to avoid losing access.
    3. When you're ready to push, use this link for the remote instead of the conventional: `git remote add origin https://User:Token@github.com/user/repository.git`

## Conclusion

This concludes our exploration of **Git**. In theory, you can already create a complete website before delving into the _Back-end_ part. However, there's much more to discover in terms of tools and technologies that will facilitate and speed up the development process. Moreover, these skills are highly sought after and almost mandatory when job hunting.
