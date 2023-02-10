---
theme: unicorn
colorSchema: 'light'

defaults:
    website: 'jimbobbennett.dev'
    handle: 'jimbobbennett'
    logoHeader: ''

layout: intro
introImage: 'https://jimbobbennett.dev/images/png/jim-portrait-circle.png'
---

# Team contribution time!

<!--

For this afternoon we are going to continue making contributions. This time, we're going to think about the different ways we can contribute to our CubeFlyer project

-->

---

# We need issues

Before we make a contribution, we should create issues for the work we want to do.

In open source, you shouldn't raise a PR without an issue (with the exception of tiny changes like typo fixes).

<!--

When you work on open source, you shouldn't do any work without it being approved up front, and this is where issues come in. If an issue is raised and not closed, it means it's something you can work on.

Only PRs without issues are tiny changes like typos.

We have defined some issues for you for this afternoon, and automated creating them.

-->

---
layout: image-center
image: 'actions.png'
image-width: '800'
---

# Project owners - create issues

We have created a GitHub action to create issues for this afternoon

<!--

Project owners - in the upstream repo, select the Actions tab
Select the _Create issues for day 2 on demand_ action, then select run workflow then run workflow.
This will automatically create issues for this afternoon. Give the workflow a few minutes to run and the issues will be created.

-->

---
layout: image-center
image: 'new-issues.png'
image-width: '800'
---

<!--

These are the issues that have been created.

-->

---
layout: center
---

# The issues

In your teams, pick an issue to work on

---

# Project management

>One challenging part of managing open source projects is governance and management. Most developers want to write code, not manage a project, which is where project, product and program management comes in.
>
> The CubeFlyer project has been run without much governance so far, so is in need of being managed.
>
> As a **project management** team, you have been tasked with:
>
> * Organizing all the open issues into projects
> * Adding appropriate labelling
> * Defining the workflow for contributing to the project
> * Adding a CLA that must be agreed to before contributing
> * Adding issue templates
> * Adding relevant protections to ensure compliance to the contribution rules
>
> For some of these tasks, members of your team may need admin rights on the repository. The project owner should be able to enforce this

---

# Documentation

> One of the most needed parts of open source projects is documentation. Many developers will want to work on code, but few want to work on docs. This is a shame, as docs are the most important part of an open source project for a new person to start using it. You can have the most perfect library, but it is useless if no-one knows how to use it.
> 
> The CubeFlyer project is lacking in good documentation.
> 
> As a **documentation** team, you have been tasked with actually creating documentation. This includes:
> 
> * A markdown file with a guide to running the project locally
> * Documentation on the structure of the code, also as a markdown file
> * Documentation for the features being added by other teams
> 
> This documentation should all be in markdown. To add documentation for features being added by other teams, you will need to collaborate with those teams to generate the documentation in tandem. This will be good learning for the other teams to help cement the idea that documentation is a continuous process that includes everyone.

---

# Deploy to the cloud

> **This is an advanced task and is only recommended for attendees with cloud experience.**
> 
> As CubeFlyer grows with web APIs to manage configuration and scores, and who knows what extra features, the game will need to deployed and managed in the cloud. This goes beyond using GitHub pages to host the site and a local configuration service.
> 
> As a **cloud engineering** team, you have been tasked with:
> 
> * Using a static hosting service to host the game site
> * Providing a hosted web API for configuration hosted in the cloud
> * Automating the deployment of both services when code is merged
> 
> What platform you use is up to you. Ideally you want to use a free service, and ensure you delete it after you have finished. It can take time to sign up for cloud services, and potentially need a credit card, so this task should only be undertaken by more advanced teams.

---

# Add a configuration service

> The game is fun with the current configuration of greetings and gravity, and it may have a local high score if this was implemented by teams in day 1. It would be nicer if this could all be in a service running somewhere that would allow the configuration to be updated without having to change the game code, or for high scores to be persisted.
> 
> A lot of software does this - it has certain values set from a configuration service that can be tweaked without redeploying the application based on data gathered from users of the application. For example, in a game if a lot of users are failing to defeat a certain boss, the game can be tweaked through configuration to make the boss easier to beat.
> 
> As a **software engineering** team, you have been tasked with:
> 
> * Creating a service that hosts a web API that you can use to retrieve configuration every time the page is refreshed
> * Adding the ability to store high scores using this web API.
> 
> How this is created is up to the team. It can be a local Python/Flask web app that stores the scores in memory, it can use a database to store the scores and configuration, use a cloud-based gaming service, or even a cloud-based serverless application. It depends on the skill level of the team, though the recommendation is to start as simple as possible.

---

# Continuous integration and deployment

> CubeFlyer is fun to play locally, but how much better would it be if your friends could play?
> 
> One way to do this is to deploy the game to a static site hosting service. Static hosting services are web hosts that serve up HTML files, but don't run any server-side code. This is fine for CubeFlyer as it is a self-contained HTML file with the game logic as JavaScript that runs locally.
> 
> The easiest static hosting service to use with GitHub is [GitHub pages](https://pages.github.com). This takes code from a GitHub repo and hosts it as a web site. 
> 
> As a **devops** team, you have been tasked with:
> 
> * Deploying the contents of the `game` folder to GitHub pages
> * Ensuring that every time the game is updated, a new deploy happens, testing this out with some basic changes
> 
> The deploy on every update can be achieved with GitHub actions, workflows that are configured and run inside a repository.

---

# Art and design

> The CubeFlyer game has graphics that are somewhat basic - it is a cube flying through blocks. This can be improved, so those attendees with an art or design background can help make both the UI and the game graphics better.
> 
> An a **user interface** team, you have been tasked with:
> 
> * Changing the cube for a different object
> * Improving the look of the columns
> * Making general improvements to the user interface such as color schemes, fonts, or the layout

---

# Other

If you want to make other changes then do so!

Raise an issue first then work on it.

---
layout: center
---

# Form new teams based off your area of interest

<!--

Project owners - decide which issue you want to work on.

When you have decided, lets form groups based off interest and get to work

-->

---
layout: center
---

# Get cracking!



---
layout: center
---

# Home work

Continue working on these issues with your team mates after this event.

This will allow you to practice working remotely.

