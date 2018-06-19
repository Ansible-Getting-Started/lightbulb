### This guide is meant to explain how to fill out our skeleton decks.
 Currently for internal use only but will be moving to community once a more stream lined approach is found.

##Creating and using the presentation

#The Slides
Each slide, starting from the very beginning can be found in the `<section>` headers. Once there, you can add anything you want in a number of ways. Depending on how you want to add them, you can add them with `<p> paragraphs` or with `<li> lists`

Speaker notes are found at the **bottom** of each section/slide. Before the slide ends `</section>` there are the opening and close of `<aside>` which is where you can put your speaker notes.

You can do a deep dive in this slides as well. To put slides below another slide, lets say for instance if you want to have steps listed for a demo, then you can put a section under a section. so the syntax would look something like this:

`<section>
  <h1>top slide</h1>
    <p>some stuff</p>
    <section>
      <h1>Another slide under the previous one</h1>
    </section>
  </section>`
