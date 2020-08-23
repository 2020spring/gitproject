# Using Git for Version Control


## Week 4 (Afterword D)
Version control software allows you to take snapshots of a project whenever it’s in a working state. When you make changes to a project—for example, when you implement a new feature—you have the option of reverting back to a previous working state if the project’s current state isn’t functioning well. 
Using version control software gives you the freedom to work on improvements and make mistakes without worrying about ruining your project. This is especially critical in large projects, but can also be helpful in smaller projects, even when you’re working on programs contained in a single file.

### CREATE REPOSITORIES
Start a new repository or obtain one from an existing URL.

Creates a new local repository with the specified name
```bash
$ git init [project-name]
```

Downloads a project and its entire version history
```bash
$ git clone [url]
```
For more download the [git cheatsheet](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf).

Find [GitHub Desktop guide](https://help.github.com/en/desktop/getting-started-with-github-desktop/creating-your-first-repository-using-github-desktop) here.

## Steps to clone the project 
1. Copy the url of the repository ending with .git (https://github.com/2019-spring/week2.git)
2. GitHub Desktop: 
    * Go to Current Repository
    * click on Add drop down
    * Clone Repository
    * click on URL tab
    * paste the copied URL (https://github.com/2020spring/gitproject.git)
    * choose the location from your local machine `C:\dev\` then click on Clone.

    Git Bash: navigate to the right directory `C:\dev\` and enter following:
  ```bash
  git clone https://github.com/2020spring/gitproject.git
  ```

  3. [optional] Create your feature branch: 
  ```bash
  git checkout -b gitproject_john
  ```
  4. Open the `C:\dev\gitproject` folder from your PyCharm and start modifying the code.

## References

* [GitHub Guides](https://guides.github.com/activities/hello-world/)
* [CS50 - Git and GitHub (video)](https://youtu.be/eulnSXkhE7I)
* [git cheatsheet](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf)
* [GitHub Desktop Documentation](https://help.github.com/en/desktop/getting-started-with-github-desktop/creating-your-first-repository-using-github-desktop)