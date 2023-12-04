### 0x03. Git

**Concepts**
--------------

For this project, we expect you to look at these concepts:

[Right-engineering, right-documenting](https://intranet.alxswe.com/concepts/6 "Right-engineering, right-documenting")

[Source code management](https://intranet.alxswe.com/concepts/22 "Source code management")

[Git and Github cheat sheet - Everything in less than 30 seconds](https://intranet.alxswe.com/concepts/57 "Git and Github cheat sheet - Everything in less than 30 seconds")

[Authenticating Git](https://intranet.alxswe.com/concepts/100035 "Authenticating Git")

[Struggling with the sandbox? Try this: Using Docker & WSL on your local host](https://intranet.alxswe.com/concepts/100039 "Struggling with the sandbox? Try this: Using Docker & WSL on your local host")

----------------------------------------------------------------------------------------------------------------------------

### Resources

**Read or watch:**

[Resources to learn Git](https://intranet.alxswe.com/rltoken/YtcpriOT-x-WiyScwLpn4Q "Resources to learn Git")

[About READMEs](https://intranet.alxswe.com/rltoken/R7MeJ8alpK3JoVF8w24wiQ "About READMEs")

[How to write a Git commit message](https://intranet.alxswe.com/rltoken/FYsjjR-97Hk4NJtgqzWdtQ "How to write a Git commit message")

**Resources for advanced tasks** (Read only after finishing the mandatory tasks):

[Learning branching](https://intranet.alxswe.com/rltoken/tN8ZJ0yWubOP6jdciqtrFw "Learning branching")

[Effective pull requests and other good practices for teams using GitHub](https://intranet.alxswe.com/rltoken/mjpQ9OCU0Dz-DFxZjASEJg "Effective pull requests and other good practices for teams using GitHub")

### Learning Objectives

At the end of this project, you are expected to be able to [explain to anyone](https://intranet.alxswe.com/rltoken/jj0uPL9hiKF10KCH4u620A "explain to anyone"), without the help of Google:

**General**

-	What is source code management
-	What is Git
-	What is GitHub
-	What is the difference between Git and GitHub
-	How to create a repository
-	What is a README
-	How to write good READMEs
-	How to commit
-	How to write helpful commit messages
-	How to push code
-	How to pull updates
-	How to create a branch
-	How to merge branches
-	How to work as collaborators on a project
-	Which files should and which files should not appear in your repo

### Requirements

**General**

-	A `README.md` file at the root of the `alx-zero_day` repo, containing a description of the repository
-	A `README.md` file, at the root of the folder of this project (i.e. `0x03-git`), describing what this project is about
-	**Do not use GitHub’s web UI**, but the command line to perform the exercise (except for operations that can not possibly be done any other way than through the web UI). You won’t be able to perform many of the task requirements on the web UI, and you should start getting used to the command line for simple tasks because many complex tasks can only be done via the command line.
-	Your answer files should only contain the command, and nothing else

### More Info

**Basic usage**

At the end of this project you should be able to reproduce and understand these command lines:

```

$ git clone <repo>

$ touch test

$ git add test

$ git commit -m "Initial commit"

$ git push origin main

```

### Tasks

### 0. Create and setup your Git and GitHub account

mandatory


**Step 0 - Create an account on GitHub [if you do not have one already]**

You will need a GitHub account for all your projects at ALX. If you do not already have a github.com account, you can create an account for free [here](https://intranet.alxswe.com/rltoken/1vpH3ScWYjfgZD0J59jusA "here")

**Step 1 - Create a Personal Access Token on Github**

To have access to your repositories and authenticate yourself, you need to create a Personal Access Token on Github.

You can follow [this tutorial](https://intranet.alxswe.com/rltoken/coQUsDnam4suGaXSVinQxA "this tutorial") to create a token.

Once it’s created, you should have a token that looks like this:

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/a449483cd76a72cef1b42df831e686c64faa1cf6.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20231204%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20231204T152356Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=72bda7c008e0051a82daa1b0a3a96d67e349aab2d1e927cbf5bcb581f800d09b)

