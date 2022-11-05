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

1. Navigate to the relevant folder

1. Run the following command to install SliDev:

    ```bash
    npm install
    ```

1. Run the following command to start SliDev:

    ```bash
    npx slidev
    ```

1. This will launch SliDev on your local host at port 3030. You can open the slide deck at [localhost:3030](http://localhost:3030).

1. If you want to access speaker notes, you can get to these from [localhost:3030/presenter](http://localhost:3030/presenter/). This presenter view will allow you to control the slide deck, see the current and next slide, see the speaker notes, and annotate the slide if required.

## List of presentations

* [Get signed up for GitHub](./get-signed-up-with-github/)
* [Contributions, CLAs, and License agreements](./contributions-licensing/)
