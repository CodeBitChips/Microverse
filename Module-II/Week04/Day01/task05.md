# Try Gitflow

## Learning objectives
- Follow Gitflow.

### Estimated time: 0.5h

## Exercise

In this exercise, you will practice Gitflow with an empty repo. As all the upcoming projects will require you to use Gitflow, make sure that you understand it very well.

*IMPORTANT NOTE: Read **all** instructions before you start this exercise.*

### Instructions

- Create a new repo. Initialize it with an empty README file.
    <p>
     <img src="../images/initialize-with-readme.png" alt="Initialize repo with readme" width="400px" />
    </p>
- Clone the newly created repository to your local machine.
- Add a new branch named `dev`(alternative names: `development`, `develop`).
- Make sure that the `dev` branch is pushed to GitHub.
    - `git push --set-upstream origin dev`
- Make the `dev` branch [the default branch](https://docs.github.com/en/github/administering-a-repository/managing-branches-in-your-repository/changing-the-default-branch#changing-the-default-branch).
- Create a feature branch called add-quotes
- Add a programmer.txt file with the following sentence (typo is needed there):
     - "A good programmer is someone who always looks both ways before crosing a one-way street."
- Add a solve.txt file with the following sentence:
     - "First, solve the problem. Then, write the code." – John Johnson
- Add another test.txt file. It should be empty.
- Commit all files to your feature branch.
- Push your changes to GitHub.
- Open a new pull request from `add-quotes` into `dev`.
- Make sure that you want to merge your commits into **dev** branch. You should add a comment in your opened pull request that is similar to this one:
     <p>
     <img src="../images/feature-branch-to-dev.png" alt="Initialize repo with readme" width="400px" />
    </p>
- _Keep your pull request open. you will need it in the upcoming exercises._
 - Congratulations! You have used Gitflow for the first time. **Remember to use it in all upcoming Microverse projects.**

### Submit your exercise
[Read this FAQ for a reminder on how to submit your exercise.](https://microverse.zendesk.com/hc/en-us/articles/360061344234)
Now go to your Student Dashboard and submit your exercise.
Paste the link to your opened pull request.

------

_If you spot any bugs or issues in this activity, you can [open an issue with your proposed change](https://github.com/microverseinc/curriculum-transversal-skills/blob/main/git-github/articles/open_issue.md)._