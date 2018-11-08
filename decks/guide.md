# Skeleton Deck Contribution Guide
This guide is meant to explain how to fill out our skeleton deck.  The decks can be found in the `decks/` directory out on its own. 

## Creating and using the presentation

#### The Slides
Each slide, starting from the very beginning can be found in the `<section>` headers. Once there, you can add anything you want in a number of ways. Depending on how you want to add them, you can add them with `<p> paragraphs` or with `<li> lists`

Speaker notes are found at the **bottom** of each section/slide. Before the slide ends `</section>` there are the opening and close of `<aside>` which is where you can put your speaker notes.

You can do a deep dive in these slides as well. To put slides below specific slide, lets say for instance if you want to have steps listed for a demo, then you can put a section under a section. The syntax would look something like this:

```
<section>
	<h1>top slide</h1>
    <p>some stuff</p>
    <section>
      <h1>Another slide under the previous one</h1>
    </section>
</section>
```

#### Presenting the slides
To use the slides, simply find them locally and double click to launch them. It will default to your default browser and you can navigate through the slides using the arrow keys. 

If you added a drop down in your slides, when you get to that slide, you will be able to navigate down using the arrow keys. Depending on how many you added, once you get to your last one, you can simply push right and that will take you up and to the next slide. 

