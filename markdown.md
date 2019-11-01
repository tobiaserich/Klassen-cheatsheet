Markdown is a lightweight and easy-to-use syntax for styling all forms of writing on the GitHub platform.

**What we need to know:**

- How the Markdown format makes styled collaborative editing easy
- How Markdown differs from traditional formatting approaches
- How to use Markdown to format text
- How to leverage GitHub’s automatic Markdown rendering
- How to apply GitHub’s unique Markdown extensions

## What is Markdown?

Markdown is a way to style text on the web. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like # or \*.

## Syntax guide

Here’s an overview of Markdown syntax that we can use anywhere on GitHub.com or in your own text files.

# Italics and Bold

\_This text will be italic\_

\*This text will be italic\*

---

\_\_This text will be bold\_\_

\*\*This text will be bold\*\*

Of course, you can use \_both italics and bold\_ in the same line, and also span them across multiple words.

# Headers

\#This is a h1

\##This is a h2

\###This is a h3

\####This is a h4

\#####This is a h5

\######This is a h6

# Links

There are two different link types in Markdown, but both of them render the exact same way.
The first link style is called an inline link.
To create an inline link, you wrap the link text in brackets [ ] , and then you wrap the link in parenthesis ( ).

Example: [Visit GitHub!](www.github.com)

    [Visit GitHub!](www.github.com)

The other link type is called a reference link. As the name implies, the link is actually a reference to another place in the document. Here's an example of what we mean:

     Here's [a link to something else][another place].
     Here's [yet another link][another-link].
     And now back to [the first link][another place].

     [another place]: www.github.com
     [another-link]: www.google.com

# Images

Images also have two styles, just like links, and both of them render the exact same way. The difference between links and images is that images are prefaced with an exclamation point ! .

The first image style is called an inline image link. To create an inline image link, enter an exclamation point ( ! ), wrap the alt text in brackets [ ] , and then wrap the link in parenthesis ( ) .

Example:

    ![Benjamin Bannekat](https://octodex.github.com/images/bannekat.png)

For a reference image, you'll follow the same pattern as a reference link. You'll precede the Markdown with an exclamation point, then provide two brackets for the alt text, and then two more for the image tag, like this: ![The founding father][father] At the bottom of your Markdown page, you'll define an image for the tag, like this: [Father]: http://octodex.github.com/images/founding-father.jpg.

Example:

    ![Black cat][Black]

    ![Orange cat][Orange]

    [Black]: https://upload.wikimedia.org/wikipedia/commons/a/a3/81_INF_DIV_SSI.jpg
    [Orange]: http://icons.iconarchive.com/icons/google/noto-emoji-animals-nature/256/22221-cat-icon.png

# Blockquotes

To create a block quote, all you have to do is preface a line with the "greater than" caret >.

Example:

    > "In a few moments he was barefoot, his stockings folded in his pockets and his
      canvas shoes dangling by their knotted laces over his shoulders and, picking a
      pointed salt-eaten stick out of the jetsam among the rocks, he clambered down
      the slope of the breakwater."

# Lists

There are two types of lists in the known universe: unordered and ordered. That's a fancy way of saying that there are lists with bullet points, and lists with numbers.

To create an unordered list, you'll want to preface each item in the list with an asterisk \* . Each list item also gets its own line. For example, a grocery list in Markdown might look like this:

    * Milk
    * Eggs
    * Salmon
    * Butter

This Markdown list would render into the following bullet points:

- Milk
- Eggs
- Salmon
- Butter

An ordered list is prefaced with numbers, instead of asterisks.

    1. Crack three eggs over a bowl
    2. Pour a gallon of milk into the bowl
    3. Rub the salmon vigorously with butter
    4. Drop the salmon into the egg-milk bowl

1. Crack three eggs over a bowl
2. Pour a gallon of milk into the bowl
3. Rub the salmon vigorously with butter
4. Drop the salmon into the egg-milk bowl

Occasionally, you might find the need to make a list with more depth, or, to nest one list within another. Have no fear, because the Markdown syntax is exactly the same. All you have to do is to remember to indent each asterisk one space more than the preceding item.

For example, in the following list, we're going to add some sub-lists to each "main" list item, describing the people in detail:

    * Tintin
      * A reporter
      * Has poofy orange hair
      * Friends with the world's most awesome dog
    * Haddock
      * A sea captain
      * Has a fantastic beard
      * Loves whiskey
      * Possibly also scotch?

- Tintin
  - A reporter
  - Has poofy orange hair
  - Friends with the world's most awesome dog
- Haddock
  - A sea captain
  - Has a fantastic beard
  - Loves whiskey
  - Possibly also scotch?

# Paragraphs

If you forcefully insert a new line, you end up breaking the togetherness:

---

If you’d like to know more about these Markdown implementations, you’re welcome to explore any number of other Markdown apps and tutorials. Here are just a few:

- https://daringfireball.net/projects/markdown/

- https://spec.commonmark.org/dingus/

- https://johnmacfarlane.net/babelmark2/faq.html

- https://www.markdownguide.org

- https://dave.autonoma.ca/blog/2019/05/22/typesetting-markdown-part-1/

- http://idratherbewriting.com/2013/06/04/exploring-markdown-in-collaborative-authoring-to-publishing-workflows/

- https://en.wikipedia.org/wiki/Markdown#Example
