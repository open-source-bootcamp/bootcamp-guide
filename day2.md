# Day 2 - get started with open source

The aim of day 2 is to teach attendees about open source software, how it can improve their career, and some of the logistics around contributing.

## Run of the day

| Time  | Activity |
| ----- | -------- |
| 09:30 | [Doors open and breakfast](#doors-open-and-breakfast) |
| 10:00 | [Welcome](#welcome) |
| 10:15 | [Networking activity - CubeFlyer competition](#networking-activity---cubeflyer-competition) |
| 10:30 | [Contributions, licensing, and CLAs](#contributions-licensing-and-clas) |
| 11:00 | [Learn about open source talks](#learn-about-open-source-talks) |
| 12:00 | [Lunch](#lunch) |
| 12:55 | [Another networking activity](#networking-activity) |
| 13:00 | [Team contributions to CubeFlyer](#team-contributions-to-cubeflyer) |
| 15:00 | [Wrap up](#wrap-up) |

## Doors open and breakfast

This is the same as [day 1](./day1.md#doors-open-and-breakfast).

## Welcome

This is the same as [day 1](./day1.md#welcome). Although these topics were covered in day 1, it is important to share the same information again as some attendees may have not attended the first day.

It is also very important to work through the code of conduct again.

## Networking activity - CubeFlyer competition

As a fun opening activity, you can get attendees to compete against each other using the CubeFlyer game from day 1. The 'winner' is the player with the longest flight time.

You can read about 2 versions of this competition in the [networking activities guide](./networking-activities.md#cube-off).

## Contributions, licensing, and CLAs

This is a session that covers a very important area for contributing to open source, the legal side. When covering this session, unless the speaker is a software lawyer, it is important to state that the speaker is not a lawyer, and this is only developer level guidance, and the attendees should consult a lawyer if they have specific questions.

You can find this session in the [presentations/contributions-licensing](./presentations/contributions-licensing/) folder.

## Learn about open source talks

This is a chance for speakers to give talks on a range of topics around open source software and contributions. You will need to find speakers to run these sessions, and topics could include:

* How I got a job thanks to open source
* A dive into a project I contribute to
* My open source origin story, or how I started contributing to open source
* What is a GitHub campus expert?
* How my company uses open source software
* A walk through of the last open source contribution I made
* A live coding session finding and fixing an issue in an open source project

These sessions are a great way to help the attendees understand more about the culture of open source. It allows them to talk to people who are involved in open source and learn more about how they get started with it, the value of it, and how it can contribute to their career.

Sessions can be as short or long as required. It would be better to go for two or more short talks, than one long one as this would give the attendees a wider scope of information.

Local speakers are better for this as an in-person event as they can stay around to network with attendees over lunch and answer any questions they have. If you are unable to find local speakers, then remote can work as long as there is a way for the attendees to ask questions not only as a part of the session, but afterwards as well.

Check out the [Mentors section in the how to run this event guide](./how-to-run-this-event.md#mentors) for some suggestions on finding local speakers.

## Lunch

This is the same as [day 1](./day1.md#lunch).

## Networking activity

This is the same as [day 1](./day1.md#networking-activity). Ideas for such activities are given [in the Networking activities guide](./networking-activities.md).

## Team contributions to CubeFlyer

This 2-hour session is for attendees to make additional contributions to CubeFlyer based upon their area of interest, and learn in groups any additional skills needed to make these contributions.

The goal is to get the attendees thinking about the different ways they can contribute to open source projects, and learn new skills to work towards this goal.

Before this section starts, create issues in the organizers CubeFlyer repo with the following tasks listed. Add these on day 2 so that folks don't work on these for day 1. You can add these as issues using the task heading as the title, and the contents under each heading in this document as the description.

These tasks are intentionally vague in how they are to be implemented with minimal hand-holding, The aim is for teams to work out how to make what they think is a good contribution. Attendees should communicate in issues and PRs to ensure their though processes are documented and to help them get used to an asynchronous workflow, as often when working on open source projects you won't be in the same room as your co-contributors.

Contributions should be made to the organizers CubeFlyer repository. The organizer should keep this repository around for a while after the event and work on helping to merge PRs so that attendees can carry on their learning after the event. The 'homework' for the attendees is to continue working on these contributions, collaborating with each other in GitHub issues and PRs.

Each of these items should be created as an issue in the CubeFlyer repository so the attendees have a place to communicate and document their work. To help you, we have created a GitHub action to create these issues automatically, and you can run this in your repo. You can find instructions in the [day2 section of the set up CubeFlyer guide](./set-up-cubeflyer.md#day-2).

### Project management

One challenging part of managing open source projects is governance and management. Most developers want to write code, not manage a project, which is where project, product and program management comes in.

The CubeFlyer project has been run without much governance so far, so is in need of being managed.

As a **project management** team, you have been tasked with:

* Organizing all the open issues into projects
* Adding appropriate labelling
* Defining the workflow for contributing to the project
* Adding a CLA that must be agreed to before contributing
* Adding issue templates
* Adding relevant protections to ensure compliance to the contribution rules

> For some of these tasks, members of your team may need admin rights on the repository. The event organizer should be able to enforce this

To help you learn some of these concepts, you can check out the following learning resources:

* [Create a release based workflow lab on GitHub skills](https://github.com/skills/release-based-workflow)
* [GitHub issues documentation](https://docs.github.com/issues/tracking-your-work-with-issues)
* [GitHub projects documentation](https://docs.github.com/issues/planning-and-tracking-with-projects)
* [GitHub labelling documentation](https://docs.github.com/issues/using-labels-and-milestones-to-track-work)
* [CLA assistant](https://cla-assistant.io/)

### Documentation

One of the most needed parts of open source projects is documentation. Many developers will want to work on code, but few want to work on docs. This is a shame, as docs are the most important part of an open source project for a new person to start using it. You can have the most perfect library, but it is useless if no-one knows how to use it.

The CubeFlyer project is lacking in good documentation.

As a **documentation** team, you have been tasked with actually creating documentation. This includes:

* A markdown file with a guide to running the project locally
* Documentation on the structure of the code, also as a markdown file
* Documentation for the features being added by other teams

This documentation should all be in markdown. To add documentation for features being added by other teams, you will need to collaborate with those teams to generate the documentation in tandem. This will be good learning for the other teams to help cement the idea that documentation is a continuous process that includes everyone.

To help you learn markdown syntax, you should work through the [Communicate using Markdown lab on GitHub skills](https://github.com/skills/communicate-using-markdown).

VS Code has great support for markdown built in, and its markdown functionality can be improved using a number of extensions. You can learn more in the [markdown in VS Code documentation](https://code.visualstudio.com/docs/languages/markdown).

### Art and design

The CubeFlyer game has graphics that are somewhat basic - it is a cube flying through blocks. This can be improved, so those attendees with an art or design background can help make both the UI and the game graphics better.

An a **user interface** team, you have been tasked with:

* Changing the cube for a different object
* Improving the look of the columns
* Making general improvements to the user interface such as color schemes, fonts, or the layout

<!--
    @runewake2 - can you add guidance here including links to relevant babylonjs docs.
-->

### Continuous integration and deployment

CubeFlyer is fun to play locally, but how much better would it be if your friends could play?

One way to do this is to deploy the game to a static site hosting service. Static hosting services are web hosts that serve up HTML files, but don't run any server-side code. This is fine for CubeFlyer as it is a self-contained HTML file with the game logic as JavaScript that runs locally.

The easiest static hosting service to use with GitHub is [GitHub pages](https://pages.github.com). This takes code from a GitHub repo and hosts it as a web site. 

As a **devops** team, you have been tasked with:

* Deploying the contents of the `game` folder to GitHub pages
* Ensuring that every time the game is updated, a new deploy happens, testing this out with some basic changes

The deploy on every update can be achieved with GitHub actions, workflows that are configured and run inside a repository.

To help you learn about GitHub pages, you should work through the [GitHub pages lab on GitHub skills](https://github.com/skills/github-pages). You can also use the [GitHub pages documentation](https://docs.github.com/pages).

To help you learn about GitHub actions, there are [multiple GitHub actions labs on GitHub skills](https://skills.github.com/#automate-workflows-with-github-actions) that you can work through, using the [GitHub actions documentation](https://docs.github.com/actions) for further reference.

### Add a configuration service

The game is fun with the current configuration of greetings and gravity, and it may have a local high score if this was implemented by teams in day 1. It would be nicer if this could all be in a service running somewhere that would allow the configuration to be updated without having to change the game code, or for high scores to be persisted.

> A lot of software does this - it has certain values set from a configuration service that can be tweaked without redeploying the application based on data gathered from users of the application. For example, in a game if a lot of users are failing to defeat a certain boss, the game can be tweaked through configuration to make the boss easier to beat.

As a **software engineering** team, you have been tasked with:

* Creating a service that hosts a web API that you can use to retrieve configuration every time the page is refreshed
* Adding the ability to store high scores using this web API.

How this is created is up to the team. It can be a local Python/Flask web app that stores the scores in memory, it can use a database to store the scores and configuration, use a cloud-based gaming service, or even a cloud-based serverless application. It depends on the skill level of the team, though the recommendation is to start as simple as possible.

### Deploy to the cloud

**This is an advanced task and is only recommended for attendees with cloud experience.**

As CubeFlyer grows with web APIs to manage configuration and scores, and who knows what extra features, the game will need to deployed and managed in the cloud. This goes beyond using GitHub pages to host the site and a local configuration service.

As a **cloud engineering** team, you have been tasked with:

* Using a static hosting service to host the game site
* Providing a hosted web API for configuration hosted in the cloud
* Automating the deployment of both services when code is merged

What platform you use is up to you. Ideally you want to use a free service, and ensure you delete it after you have finished. It can take time to sign up for cloud services, and potentially need a credit card, so this task should only be undertaken by more advanced teams.

> Do **not** share cloud credentials or access with teammates unless you know what you are doing t control access. You don't want a teammate to accidentally spin up extra services that cost you money.

Some suggestions to help you learn how to do this are:

* [Azure static web apps on Microsoft Learn](https://learn.microsoft.com/training/paths/azure-static-web-apps/)
* [Build an AI web app by using Python and Flask on Microsoft Learn](https://learn.microsoft.com/training/modules/python-flask-build-ai-web-app/)

## Wrap up

At the end of the day, you will need to wrap up the event. Take a moment to thank all the mentors, and give a very quick review of the whole event.

Close by encouraging attendees to get involved with open source. Give them 'homework' to continue making contributions to the CubeFlyer project, and ensure the repo is available for a while afterwards, with mentors who can review and merge PRs.

You can find an example wrap up deck in the [presentations/day-2-wrap](./presentations/day-2-wrap/) folder. Instructions on using this deck are in the [README in the presentations folder](./presentations/README.md).
