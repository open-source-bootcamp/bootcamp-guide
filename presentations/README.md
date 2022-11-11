# Presentations

This folder contains the presentations needed to deliver this bootcamp.

Each subfolder contains the content for the presentation, including all slides in a file called `slides.md`. This markdown file contains the slides in the required format for [SliDev](https://sli.dev), a tool for presenting slides inside your browser.

> The slides look best in Edge or Chrome. The rendering in Safari looks a little wonky with outlines around some titles.

## Personalizing the slides

Each slide markdown file has a first slide to introduce the speaker. You will need to set a number of fields in the front matter and the first slide to match the presenter:

* Set the value for the `website` field to the presenters website (for example your GitHub page) if you want a link on every page.
* Set the value for the `handle` field to the presenters social handle (for example your Twitter handle) if you want this on every page
* Set the value of the `logoHeader` to an image file for the presenter or the presenters companies logo if you want this on every page
* Replace `Name` in the first slide with the presenters name.
* Set the `introImage` value with a link to an image of the presenter
* Add any extra introductions as needed - for example adding your open source origin story showing how you got into contributing to open source

## Using the slides

To use the slides:

1. Clone this repo

1. From the `presentations` directory run the following command to install SliDev:

    ```bash
    npm install
    ```

1. Launch the presentations using one of the provided scripts:

    *. Intro to GitHub: `npm run intro`
    *. Licensing Contributions: `npm run licensing`
    *. Sign Up for GitHub: `npm run signup`

1. This will launch SliDev on your local host at port 3030. You can open the slide deck at [localhost:3030](http://localhost:3030).

1. If you want to access speaker notes, you can get to these from [localhost:3030/presenter](http://localhost:3030/presenter/). This presenter view will allow you to control the slide deck, see the current and next slide, see the speaker notes, and annotate the slide if required. The speaker notes are included as HTML comments in the markdown in the `slide.md` files.

## List of presentations

* [Get signed up for GitHub](./get-signed-up-with-github/)

    These slide includes a slide for the GitHub student developer pack. If your audience does not include students then remove this slide. Instructions to do this are inline in the `slides.md` file.

* [Introduction to GitHub](./intro-to-github/)

    These slides have embedded YouTube videos. You will need to ensure you are presenting in a way that the audience can hear the audio from your computer. If not, you **MUST** turn on captions on the videos. Ideally captions should always be turned on.

    There is also an image of a GitHub profile taken from [@JimBobBennett](https://github.com/JimBobBennett). Replace this with an equivalent screenshot of your own GitHub profile.

* [Contributions, CLAs, and License agreements](./contributions-licensing/)

## FAQ

* **Why aren't these slides hosted somewhere so I don't need to clone this repo**

    Great question! We wanted to allow you to add your personal details like name, social handle, image etc. The easiest way to do this is for you to run these slides locally

* **Once customized with my details can I host my slides anywhere**

    Yes! From the folder containing the presentation you want to host, run:

    ```bash
    npx slidev build
    ```

    This will build a single page application (SPA) in a subfolder called `dist` that you can host with services like [GitHub pages](https://pages.github.com) or [Netlify](https://www.netlify.com).