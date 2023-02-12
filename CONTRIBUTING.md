# Why contribute?

Software developed by BlueGreen Labs is mostly done so on free time. Software bugs and mistakes are a reality, and usability can always be improved as it is often a matter of taste and or culture. **We rely on you, the user,** to point out any issues with the software and where (and how) to improve it. Below you will find a description on how to contribute if you feel a change to a package is needed.

## Phylosophy

We try to balance our personal time, the needs of the scientific community and the rigour of the code made public in our software packages. This also means that **the code comes AS IS**. Meaning with all its errors included and no guarantee. We rely on the (scientific) community to help us point out usability issues, bugs or logicla errors, points for optimization, or a lack in documentation. 

Most software written by BlueGreen Labs are well defined. The software focusses on one particular set of tasks, and tries not to be scoped to widely to keep code bases maintainable. When possible we do implement unit tests to see if code functions consistently within and between releases, and ask for outside review if written within the context of larger collaborations. We hope the latter minimizes errors overall.

# What to contribute?

## Documentation

In general software is only as accessible as the documentation provided. Documenation contributions on both functions or worked examples (e.g. from courses or research where you used the software) are always welcome.

## Issues, i.e. bugs and errors

If you notice anything which doesn't function or where you think the output is wrong, let us know! Bugs and breaking features can pop-up even with rigorous testing and code review. File an issue, or fix the issue yourself and provide a pull request. An outline of how to do both is given below.

## Optimizations

Do you find a particular process slow, and do you have a solution for it. Does a workflow not make sense? Would you like to include a new feature? In all these cases file an issue and start a discussion.

# How to contribute?

You can contribute by providing:

- raising an issue
- a pull request 

An issue just lets us know what is going on, while not necessarily providing a solution. A pull request provides a solution to the problem, which is actively pushed back to your repository. The latter is more advanced, and the process of both filing an issue or creating a pull request is explained in detail below.

## Issues

The most basic form of feedback on a software project can be made through filing a simple github issue. For this you enter the `Issues` tab on the left hand side of the project main page (the {MODISTools} package page is used as an example). Within the tab push the green `Issue` button to file a new issue.

![Screenshot from 2023-02-12 11-03-41](https://user-images.githubusercontent.com/1354258/218304642-51f0f106-fbf9-4554-accd-8daaab2393af.png)

This will create a new issue which requires a title and a description of the isuse that you are encountering. You can use markdown to structure and highlight code or text. Use a descriptive title and when possible include a reproducible example. You can include R (python, bash) code in markdown. 
When using `R` the [{reprex}](https://reprex.tidyverse.org/) package can help to create reproducible code snippets for reporting issues.

![Screenshot from 2023-02-12 10-34-13](https://user-images.githubusercontent.com/1354258/218304672-8c3063a6-2162-4934-b27c-902c08ea9823.png)

## Pull requests

Pull requests are a way to pull in changes to an original project repository from an external source, after fixing an issue, creating a feature or documentation. To create a pull request you will first have to **fork** the original repository (i.e. create a copy of the repository in your own workspace). You can create any public repository by pushing the **fork** icon in the top right corner. This will copy the content over to your github account.

You can now **clone** the project to your local computer and make any required changes (and push those back). If you have finished your work you can create a request to integrate the code into the original package using a **pull request**. To create a pull request enter the pull requests tab on the left hand side of your project, and push the green button pull `new pull request`. This will bring up a window in which to describe the reason the pull request with a brief title and summary of the changes.

![Screenshot from 2023-02-12 11-02-37](https://user-images.githubusercontent.com/1354258/218304705-53735ef0-7a26-49b6-99a3-de6ded8a5627.png)

Above you see an example of the pull request tab on a BlueGreen labs forked {rnaturalearth} `R` package (which is owned by rOpenSci).
