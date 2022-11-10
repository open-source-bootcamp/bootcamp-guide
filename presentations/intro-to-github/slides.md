---
theme: unicorn
colorSchema: 'light'

defaults:
    website: ''
    handle: ''
    logoHeader: ''

layout: intro
introImage: ''
---

# Introduction to GitHub

By: "Name"

<!-- 
Hi, I am name.

I'm here to guide you through getting started with GitHub and making your first code commits.

In this session you will all be contributing to your own repositories. In the next sessions you will start collaborating in teams.

-->

---

# What is GitHub?

GitHub is a collaboration platform that uses Git for versioning. GitHub is a popular place to share and contribute to open-source software.

<!--

GitHub is a collaboration platform that uses Git for versioning. GitHub is a popular place to share and contribute to open-source software.

-->

---
layout: center
---

<iframe width="728" height="410" src="https://www.youtube.com/embed/w3jLJU7DT5E?cc_load_policy=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<!--

Play this video, ideally in full screen, to give an introduction to GitHub.

-->

---

# Step 1: Create a repository

In this step you will create your first repository to contain information about you that you can share on your GitHub page.

<!--

For this section, we are going to create our first repository. We are actually going to create a special repository that can be used to add a description of yourself to your GitHub profile.

-->

---

# What is a repository?

A repository or 'repo' is a project containing files and folders. A repository tracks versions of files and folders.

<!--

A repo is a project containing files and folders with project code, images, and other assets. It tracks versions of your code, including who contributed these.

On GitHub a repository also has additional features including tools for tracking issues, which are items to be done such as code features or bug reports, and actions that are code that is run at times such as when your code changes. These actions can do things like run tests, or deploy a new version of your project.

-->

---
layout: center
---

<iframe width="728" height="410" src="https://www.youtube.com/embed/R8OAwrcMlRw?cc_load_policy=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<!--

Play this video, ideally in full screen, to give an introduction to repositories in GitHub. This is an older video, so be aware that the user interface (UI) has changed since this video was released.

Ignore the instruction to click around in the class repository, that is for watching this video as part of GitHub classroom learning.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/github-profile-jimbobbennett.png?raw=true'
imageWidth: '800'
---

&nbsp;

<!--

NOTE: Feel free to replace this image with an image of your own GitHub profile

Here is an example of a GitHub profile. The contents of the Overview section comes from file called README.MD from a repository that has the same name as the GitHub user.

.md files are markdown files - this is a way of writing text with styles by using characters in the text to define what style to use, or to add images, links and more. We will look more at this later.

README files are also special. When you view a repository, or a folder in a repository, if that repo or folder has a file in it called README.md, that will be shown below the list of files and folders. These README files are the standard place to put details about the project and links to further documentation if needed.

-->

---

# Activity: Create the repository

[github.com/new](https://github.com/new)

<!--

Head to GitHub.com/new to create a new repository. You can also access the same option from the + menu on the top of the Github page, or from your repositories list.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/new-repo-1.png?raw=true'
imageWidth: '700'
---

&nbsp;

<!--

If you see an option to use a template, leave it as 'No template' for now. You may not see this for your first repository.

Start by setting the repository name to be the same as your GitHub username. This will make a hit appear saying this is a special repository to add a README to your GitHub profile.

Add a description for the repo as well, such as 'My profile readme'. The description is optional.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/new-repo-2.png?raw=true'
imageWidth: '700'
---

&nbsp;

<!--

Next you can set the visibility. Public repositories are visible to all, and for your public profile you want this to be public otherwise no-one can see your profile.

Public means the code is public for anyone to view, but only you can make changes, or anyone else you give permissions to.

Private repos are private to you and anyone you add as collaborators. Organizations will also have GitHub accounts and keep their internal application code in private repos that only employees can access.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/new-repo-3.png?raw=true'
imageWidth: '700'
---

&nbsp;

<!--

Next you configure what you want pre-created in the repo.

We want a README file as this is where we will be creating our profile.

The .gitignore file is used to define what files you want to ignore. When you make changes to your code, Git tracks these and gives you the option to submit these changes to your GitHub repo. There are often files that are created that you *don't* want added to GitHub, such as packages that your code uses, or files created by building your code. These are tracked in the .gitignore file, any file or folder in the .gitignore is ignored by git and won't be added to source code control.

For now you can leave the .gitignore template set to None

Next choose a license. This defines what others can do with your code. Licenses will be covered later in this bootcamp.

For now you can leave this set to None.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/new-repo-4.png?raw=true'
imageWidth: '700'
---

&nbsp;

<!--

Finally select *Create repository* to create the repo.


NOTE: Wait for the attendees to complete this step before you move on. Ask mentors to help if needed.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/new-repo-5.png?raw=true'
imageWidth: '900'
---

&nbsp;

<!--

Once created, you will be taken to the repo.

The README will be created for you with text that says 'Hi there 👋', along with a note to show that this is a special repo.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/new-repo-6.png?raw=true'
imageWidth: '900'
---

&nbsp;

<!--

If you now go back to your profile, you will see this as the profile details. You can get back to your profile by clicking your name on the repo page. This will be the first instance - the repo is username/username, so click the first one to get your profile, or navigate to github.com/username

-->

---

# Step 2: Create a branch

In this step you will create a new branch.


A branch is a parallel version of your repository. By default, your repository has one branch named **main** and it is considered to be the definitive branch. You can create additional branches off of **main** in your repository. You can use branches to have different versions of a project at one time.

On additional branches, you can make edits without impacting the **main** version. Branches allow you to separate your work from the **main** branch. In other words, everyone's work is safe while you contribute.

> In the past, the default branch was called master. This has been changed to main to be more inclusive. You may still see references to master, or the use of master in older repositories.

<!--

Branches are parallel version of your code. You have to have at least one branch, and by default this is called main. You can make additional branches off of main to allow you to work on code without impacting main. You can then merge these changes back on to main (or to another branch if you wish). This will be covered later in this session.

In the past the default branch was known as the master branch, but this terminology is being phased out to be more inclusive and replaced by main. You may still see master being used in older repositories.

-->

---
layout: center
---

<iframe width="728" height="410" src="https://www.youtube.com/embed/xgQmu81G1yY?cc_load_policy=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<!--

Play this video, ideally in full screen, to give an introduction to branches. This is an older video, so be aware that the user interface (UI) has changed since this video was released. 

This video also refers to master instead of main.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/new-branch-1.png?raw=true'
---

# Activity: Create a new branch

<!--

From your repo, drop down the branch selector. This allows you to select a different branch to view, oe create a new branch.

Type the name `my-first-branch` into the branch selector, and you will see an option to create this branch from main. Select this to create the branch. The branch will be created, and will be selected in the branch selector, showing the code on this branch.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/new-branch-2.png?raw=true'
---

&nbsp;

<!--

There will be a note that this branch is up to date with main. Where main is the default branch, when you are on other branches you will see if the branch is ahead of or behind main - that is does main have changes that are not on your branch, or does you branch have changes not on main.

main is the default branch - so when you visit your repo by default you will see the main branch, not your new branch. If you navigate away, then come back to the repo you will need to reselect this branch. Drop down the branch selector and select your new branch from the list.

NOTE: Wait for the attendees to complete this step before you move on. Ask mentors to help if needed.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/gitgraph-first-branch.png?raw=true'
imageWidth: '500'
---

&nbsp;

<!--

We now have 2 branches. main and my-first-branch taken from the main branch

-->

---

# Step 3: Edit the README

In this step you will edit the README file.

Repositories can be cloned to make a copy of the entire repository (including a complete history) on your computer that you can edit. You can also edit files on GitHub.

In this step you will edit the code directly on GitHub.

<!--

Editing files can happen on GitHub, or you can take a copy of the repository on your computer and edit files. TO keep things easier, in this step we will edit code directly on GitHub. Later in this bootcamp you will clone the repository and edit the files on your computer.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/edit-readme-1.png?raw=true'
imageWidth: '800'
---

# Activity: Edit the README

<!--

When you view the repo, you will see a pencil icon on the README in the top corner of where the file contents is displayed.

Select the pencil to open the README in edit mode.

NOTE: Wait for the attendees to complete this step before you move on. Ask mentors to help if needed.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/edit-readme-2.png?raw=true'
imageWidth: '800'
---

&nbsp;

<!--

This opens the file in edit mode so you can make changes. This file contains text in markdown format.

Lets look through this line by line

-->

---

```markdown {1|3,16}
### Hi there 👋

<!--
**username/username** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
``` 

<!--

Line 1 starts with 3 hash characters. This is how you indicate headings. One # is a top level heading (same as h1 in HTML), and as you add hashes the heading level goes down, so ## is h2, ### is h3.

This is a third level heading saying Hi there. This heading makes the text larger than the default and bold.

The next section is commented out with HTML comments. You can put HTML in markdown and it will generally work as long as it isn't running scripts.

Inside the comments is suggested things you can put in the README.

-->

---

```markdown {4|8-15}
### Hi there 👋

<!--
**username/username** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
``` 

<!--

On line 4 there is text between double asterisks. This makes the text between these bold.

There is also text between underscores. This makes the text italic.

The README.md between the backticks makes the text look like code in a monospaced code font.

Lines that start with a - or a single asterisk are bullet points.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/edit-readme-3.png?raw=true'
imageWidth: '800'
---

# The preview tab

<!--

You can see what the markdown looks like in the Preview tab. Select this to see a preview of the markdown

-->

---

# Make some changes!

Try making some changes to the README file and preview it!

<!--

Try making some changes to the markdown and previewing it.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/edit-readme-4.png?raw=true'
imageWidth: 800
---

```markdown
# Hello there 👋

- 🔭 I’m currently working on an open source
- 🌱 I’m currently learning all about GitHub and open source
- 👯 I’m looking to collaborate on open source
```
&nbsp;

<!--

Here's an example of changes made to the file and it's preview.

NOTE: Wait for the attendees to complete this step before you move on. Ask mentors to help if needed.

-->

---

# Commit your changes

Now you have made changes, it's time to commit them.

A commit is a set of changes to the files and folders in your project. A commit exists in a branch.

<!--

A commit is a group of changes to one or more files on a branch. You commit all the changes as a single entity, so when others look at your commit history they can see all the file changes that were a part of this commit.

Each commit is listed against the username of the commiter.

Against a commit you have to have a message that describes the change.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/edit-readme-5.png?raw=true'
imageWidth: '800'
---

&nbsp;

<!--

Below the edit box for the file is the controls to commit the file.

The first box is for you to add a commit message. GitHub helpfully adds a default 'Updated README.md' but you can put something different if you want.

The description is meant to be short, and is limited to 72 characters. To add more information you can add a description, but this is optional. The description field is markdown, so you can style the text, add images, add links etc.

You then choose to commit to the current *my-first-branch* branch, or create a new branch with the commit. You want to create on the current branch.

Then select the **Commit changes** button to make the commit.

NOTE: Wait for the attendees to complete this step before you move on. Ask mentors to help if needed.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/gitgraph-first-branch-commit.png?raw=true'
imageWidth: '500'
---

&nbsp;

<!--

We now have a commit on the my-first-branch. This change is NOT on the main branch.

-->

---

# Commits only contain the changes

A commit only contains the changes made to the file (lines added or removed, text changed), not the complete file.

<!--

Commits only contain the changes made, not the entire file.

-->

---

# Step 4: Create a pull request

Now that you’ve created a commit, it’s time to share your proposed change through a pull request!

Collaboration happens on a pull request. The pull request shows the changes in your branch to other people. This pull request is going to keep the changes you just made on your branch and propose applying them to the main branch.

> 'Pull request' is often abbreviated to 'PR'

<!--

A pull request is a request to pull your changes from one branch onto another. In this case you can raise a pull request to request to pull your commit to update your README file into the main branch.

This may seem strange when it's just you working on your code, but pull requests are an important way for multiple people to collaborate on code. A pull request is an invitation to collaborators to review your code before it is accepted, and ask for any changes that are needed.

-->


---
layout: center
---

<iframe width="728" height="410" src="https://www.youtube.com/embed/kJr-PIfLDl4?cc_load_policy=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<!--

Play this video, ideally in full screen, to give an introduction to pull requests. This is an older video, so be aware that the user interface (UI) has changed since this video was released. 

This file refers to issues. These will be covered later in this bootcamp.

This video also refers to master instead of main.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/raise-pr-1.png?raw=true'
imageWidth: '800'
---

# Activity: Raise a pull request

<!--

You can now raise a pull request to copy your changes to main.

Once you make the change, the repo helpfully shows you that you have recently made changes, and shows that you are one commit ahead of main.

Select the **Compare & Pull request** button to create a pull request.

NOTE: Wait for the attendees to complete this step before you move on. Ask mentors to help if needed.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/raise-pr-2.png?raw=true'
imageWidth: '800'
---

&nbsp;

<!--

This is the pull request form. Lets look at it piece by piece.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/raise-pr-3.png?raw=true'
imageWidth: '800'
---

&nbsp;

<!-- 

When raising a PR you need to specify which branch is receiving the changes (the target branch), and which branch the changes are coming from (the source branch).

Make sure your source branch is your new my-first-branch and the target branch is the main branch.

The Pull Request is to apply the commits made to the source branch to the target branch. A PR does not copy the entire file to the target branch, just the changes. This means if the file on the target branch has additional changes that are unrelated to your commit, those will remain when your PR is merged.

There is a helpful indicator that tells you if you are able to merge your changes. Sometimes you won't be able to directly merge the changes due to conflicts - that is changes have happened on the target branch that are incompatible with the changes coming in from the source branch.

These merge conflicts will be covered in a later part of this bootcamp.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/raise-pr-4.png?raw=true'
imageWidth: '600'
---

&nbsp;

<!--

This section is for you to describe the pull request. You can give it a title and optionally a description.

Imagine you are making a big change when collaborating on an application with a team. You will need to reference any information about the reason for the change, describe the implementation, describe any testing that was done. and maybe ask for thoughts on different parts of the code change.

A Pull Request is the start of a collaborative process that includes reviews by others. With non-trivial PRs (so PRs bigger than fixing a simple spelling mistake or a config change), there are often changes requested by the collaborators including bug fixes, style changes, a request for more tests etc.

The description field is markdown, so you can style the text, add images, add links etc.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/raise-pr-5.png?raw=true'
imageWidth: '300'
---

&nbsp;

<!--

PRs are about collaboration, so you can request reviews from others who are collaborating on the same repo. You can also assign the PR to someone.

For example, you can ask Rod, Jane and Freddy for a review. When Jane picks it up the assign it to themselves during the review. If Jane then has a question for Freddy, it can be reassigned to Freddy, who can then assign it back to you if there are changes needed.

You can also attach labels to PRs. For example, you can label by product area, label bug fixes vs new functionality. label PRs that just add tests, whatever system makes sense to you.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/raise-pr-6.png?raw=true'
imageWidth: '800'
---

&nbsp;

<!--

Add a description, then select **Create pull request** to create the PR.

NOTE: Wait for the attendees to complete this step before you move on. Ask mentors to help if needed.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/raise-pr-7.png?raw=true'
imageWidth: '800'
---

&nbsp;

<!--

The pull request is now created, and you will see a count of PRs of 1 against the Pull Request tab

-->


---

# Step 5: Merge the pull request

You successfully created a pull request. You can now merge your pull request.

A merge adds the changes in your pull request and branch into the *main* branch.


<!--

Merging is the act of applying your pull request to pull the changes into the target branch, in this case the main branch.

-->


---
layout: center
---

<iframe width="728" height="410" src="https://www.youtube.com/embed/PBI2Rz-ZOxU?cc_load_policy=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<!--

Play this video, ideally in full screen, to give an introduction to pull requests. This is an older video, so be aware that the user interface (UI) has changed since this video was released. 

This video also refers to master instead of main.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/raise-pr-7.png?raw=true'
imageWidth: '800'
---

# Activity: Merge your pull request

<!--

The PR form allows you to review and merge your PR. Lets look at this in detail.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/merge-pr-1.png?raw=true'
imageWidth: '400'
---

&nbsp;

<!--

The conversation tab is where conversation happens around the issue. GitHub is great for remote and asynchronous teams as reviews can happen at any time. For example, a developer in France can raise a PR in their morning and assign it to a developer in Brazil, who might look at it and make comments in their afternoon after the French developer has gone home. The French developer will then see the comments their next morning, and be able to address these before the developer in Brazil gets to work.

To add more changes to the pull request, you make more commits to your branch, and they are automatically included in the pull request. A pull request is for all changes on a branch, not a specific set of changes from that branch. Once more changes are added, these are shown in this conversation.

From here you can also see checks such as can the code be merged, and any restrictions you put on the repo, such as needing to pass unit tests that can be automatically run, or ensuring the contributor has signed a contributor license agreement which we will look at later in this bootcamp.

You can also merge or close the PR as unmerged from here.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/merge-pr-2.png?raw=true'
imageWidth: '800'
---

&nbsp;

<!--

The commits tab shows all the commits made in this PR. You can look at individual commits to see the changes as needed.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/merge-pr-3.png?raw=true'
imageWidth: '800'
---

&nbsp;

<!--

The files changed tab shows all the files that were changed in this PR. It shows lines changed with red for text removed, and green for text added.

You can make comments in-line in this view if you want to comment on specific lines with reviewing code. These comments then appear on the conversation tab.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/merge-pr-4.png?raw=true'
imageWidth: '800'
---

&nbsp;

<!--

Let's merge this PR. We'll start by making a comment to say we are happy with the changes. Emoji's are popular for this, so a standard way to signal approval is the thumbs up emoji. Add this, then select **Comment** to make this comment.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/merge-pr-5.png?raw=true'
imageWidth: '700'
---

&nbsp;

<!--

Next, select **Merge pull request** to merge the PR.

NOTE: Wait for the attendees to complete this step before you move on. Ask mentors to help if needed.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/merge-pr-6.png?raw=true'
imageWidth: '800'
---

&nbsp;

<!--

You can add a description and title if you want - this merge becomes a commit onto the main branch, so you can provide extra information that will appear in the commit history for the branch.

Then select **Confirm merge**

NOTE: Wait for the attendees to complete this step before you move on. Ask mentors to help if needed.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/gitgraph-merge-first-branch.png?raw=true'
imageWidth: '600'
---

&nbsp;

<!--

Once merged, the commit is added to the main branch

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/merge-pr-7.png?raw=true'
imageWidth: '800'
---

&nbsp;

<!--

Once the PR is merged, the conversation is updated to show this.

The conversation also shows an option to delete the branch. If you are finished with this branch it is good practice to delete it. If it's not being used then you don't want it cluttering up the branch list. Once deleted branches can be restored if needed.

NOTE: Wait for the attendees to complete this step before you move on. Ask mentors to help if needed.

-->

---
layout: image-center
image: 'https://github.com/open-source-bootcamp/bootcamp-guide/blob/main/presentations/intro-to-github/gitgraph-main-final.png?raw=true'
imageWidth: '600'
---

&nbsp;

<!--

Finally we have 3 commits on the main branch - an initial commit which was created when the README file was generated with the repo, the update to the readme, and the merge.

-->

---

# Done!

You have successfully created your profile README!

If you want to learn more about markdown to make this look extra cool, check out the **communicate using markdown** lesson on GitHub Skills.

[skills.github.com](https://skills.github.com)

<!--

You are now done! you can learn more about markdown on the Communicate using markdown lesson on skills.GitHub.com and make your profile readme look extra special.

Top tip - profile READMEs are public, so if you find one that looks cool, you can read the markdown and copy it!

-->