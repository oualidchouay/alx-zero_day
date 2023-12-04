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

**Step 2 - Update your profile on the Intranet**

Update your Intranet profile by adding your Github username [here](https://intranet.alxswe.com/rltoken/9dthiwx9AyxxUzV_QPIRWQ "here")

If it’s not done **the Checker won’t be able to correct your work**

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/6270480a0a982cd1846b877eda2ee405d2e8f575.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20231204%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20231204T152356Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=9b1c5444bd5462f4d76b9c88d1a34bc39050372a752d077cefb4b21a5ef1386e)

**Step 3 - Create your first repository**

Using the graphic interface on the [github website](https://intranet.alxswe.com/rltoken/1vpH3ScWYjfgZD0J59jusA "github website"), create your first repository.

-	Name: `alx-zero_day`
-	Description: `I'm now a ALX Student, this is my first repository as a full-stack engineer`
-	Public repo
-	No `README`, `.gitignore`, or license

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/2340a2d0f7c74b5dd6f8fc2aa58f94d13ea2c775.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20231204%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20231204T152356Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=561cb817b9c7f607b3f034c603fa6e57fb39cadcf2178f1bed2b3aca49519594)

**Step 4 - Open the sandbox**

On the intranet, just under the task, click on the button ![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/9db8eece71455dfddf4b7d8585c037c535f1d18d.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20231204%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20231204T152356Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=580dd8a1b36b87c7f2467687d572b4ce3b8c9bb74e7b2b43ef2ab9043dacc166) and `run` to start the machine.

Once the container is started, click on ![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/be9d1fbfb3d97e6924a4d2af7df9290ad7ae77df.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20231204%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20231204T152356Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=466f9f9e2b0541f9d60d7ea8bcfcf63b0b723963f46ff6ce743ca99adb2816e2) to open a shell where you can start work from.

**Step 5 - Clone your repository**

On the webterm of the sandbox, do the following:

-	Clone your repository

```

root@896cf839cf9a:/# git clone https://{YOUR_PERSONAL_TOKEN}@github.com/{YOUR_USERNAME}/alx-zero_day.git

Cloning into 'alx-zero_day'...

warning: You appear to have cloned an empty repository.

```

**Replace {YOUR_PERSONAL_TOKEN} with your token from step 1**

**Replace {YOUR_USERNAME} with your username from step 0 and 1**

**Pro-Tip:** On windows, use CTRL + A + V to paste in the web terminal

**Step 6 - Create the README.md and push the modifications**

-	Navigate to this new directory. [Tips](https://intranet.alxswe.com/rltoken/qSP5HcBSSIL0U23PdIGKLw "Tips")

```

root@896cf839cf9a:/# cd alx-zero_day/

root@896cf839cf9a:/alx-zero_day#

```

Create the file `README.md` with the content `My first readme`. [Tips](https://intranet.alxswe.com/rltoken/_SSotigVtvVNThTVLJKZPQ "Tips")

```

root@896cf839cf9a:/alx-zero_day# echo 'My first readme' > README.md

root@896cf839cf9a:/alx-zero_day# cat README.md

My first readme

```
-	Update your git identity

```
root@896cf839cf9a:/alx-pre_course# git config --global user.email "you@example.com"

root@896cf839cf9a:/alx-pre_course# git config --global user.name "Your Name"
```

-	Add this new file to git, commit the change with this message “My first commit” and push to the remote server / origin

```
root@896cf839cf9a:/alx-zero_day# git add .

root@896cf839cf9a:/alx-zero_day# git commit -m 'My first commit'

[master (root-commit) 98eef93] My first commit

 1 file changed, 1 insertion(+)

 create mode 100644 README.md

root@896cf839cf9a:/alx-zero_day# git push

Enumerating objects: 3, done.

Counting objects: 100% (3/3), done.

Writing objects: 100% (3/3), 212 bytes | 212.00 KiB/s, done.

Total 3 (delta 0), reused 0 (delta 0)

To https://github.com/{YOUR_USERNAME}/alx-zero_day.git

 * [new branch]      master -> master
```

Good job!

You pushed your first file in your **first repository** of the **first task** of your **first ALX School project**.

You can now check your repository on GitHub to see if everything is good.

**Repo:**

-	GitHub repository: `alx-zero_day`
-	File: `README.md`


![](C:\Users\OUALID\Desktop\a449483cd76a72cef1b42df831e686c64faa1cf6.png)