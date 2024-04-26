README.md

# Git Assignment - vivitali

    > a. What is an _issue_?

    An issue on GitHub is a way to track, feature, tasks, or bugs for projects. It also serves as a discussion platform

    > b. What is a _pull request_?

    It's a method to propose your changes to the repository.  Review, discuss, aprove, run tests,  reject requests changes  it's just a small portion of the functionality

    > c. How do I open up a _pull request_?

    1) Go to pull requests tab in repository -> hit green button "New pull requests" select destination(base) branch and compare branch (it has to be branch with new changes)
    2) go to 'branches' -> find your branch -> hit ellipsis (context menu) button in the end  -> select create button

    > d. Give me a step by step guide on how to add someone to your repository.

    hit tab settings -> collaborators -> confirm actions with password/passkey/two factor auth -> hit add people -> search by username email or name. User has to accept invitation

    > e. What is the difference between `git` and `GitHub`?

    git is a version control system that lets you manage and keep track of your source code, github is a one of many cloud based services taht lrt to manage repositories. Other popular services : Bitbucket, Gitlab

    > f. What does `git diff` do?

    It displays the differences between commits, between commits and working tree, etc. It also shows what has changed in the files from your last commit.

    > g. What is the `main` branch?

    The main branch is the default development branch. Upon creation of a repository, it's the primary branch and typically used as default branc of the repository. But it can be changed or renamed in settings

    > h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the `main` branch?

    It's a bad practice to push to the main (or another default branch) directly. Much better to create new branch (feature branch) and push  changes to that branch and create Pull request. Direct pushes to default branch can be restricted in repository settings
