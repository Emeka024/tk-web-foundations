# More HTML Elements

*Estimated Time: 20 minutes*

---

<aside>


😃 This is a bonus section on other HTML tags.

You don’t need to know these, but they’re pretty cool if you have extra time!

</aside>

# Other elements and tags

As you learn more web development, you’ll see tons of other tags.

Here’s a preview of some of the tags you’ll encounter. Again - you don’t need to know these ones. Remember that you can look them up later!

### Stylized text elements

There are lots of elements for particular kinds of styled text.

Here’s some of the tags, but without examples. Don’t try to memorize them. Instead, skim them, and then remember that you can always go back and look up the right element to use for a particular situation.

- **List: stylized text elements**
    
    `<code>`: used to style blocks of code.
    
     `<pre>`: used for text that has been pre-formatted, like a poem, where the spaces are already there. Otherwise, spaces, tabs, and newlines all get collapsed by the browser.
    
    `<small>`: Small text
    
    `<u>`: Underlined text
    
    `<i>`: Italicized text
    
    `<s>`: Text with a strikethrough, like ~~this~~
    
    `<q>`: “quoted text that fits within a line”
    
    `<blockquote>`: A block quote, usually multiple lines
    
    `<mark>`: Highlighted text
    
    `<del>`, `<ins>`: Text that’s been deleted or inserted
    
    `<sub>`, `<sup>`: Subscript ($_{subscript}$) and Superscript ($^{superscript}$)
    

### S**emantic elements**

**Semantics** refers to the *meaning* of a piece of code. It’s about "*what purpose or role does that HTML element have*", rather than "*what does it look like?"*.

> When approaching which markup to use, ask yourself, "What element(s) best describe/represent the data that I'm going to populate?”

*MDN*
> 

HTML elements mean something*.* A `<p>` isn’t just styled like a paragraph, it tells other programs that the text inside *really is* a paragraph.

There are lots of kinds of “things” that go on webpages. For many of them, there’s a matching HTML element. Here’s some examples (there’s more than 100!)

- **List of Semantic Elements**
    - `<article>`
    - `<section>`
    - `<nav>`
    - `<footer>`
    - `<aside>`
    - `<details>`
    - `<summary>`
- **Further Exploration: Semantic Elements**
    
    [https://developer.mozilla.org/en-US/docs/Glossary/semantics](https://developer.mozilla.org/en-US/docs/Glossary/semantics)
    
    Questions to explore:
    
    - Why use Semantic HTML?
    - What are the benefits of Semantic Elements?
    - When would you use these?

### `<div>`, `<span>`: Generic Elements

Sometimes, you don’t know which semantic element to use. `<div>` stands for “division” and it’s a generic block of HTML. `<span>` is a generic “span” of text characters, inline with some other text. If you don’t know another element that’s more appropriate, you can use one of these instead.

Example:

```html
<div>This div has its own line.</div>
<div>
	This shows on a second line, 
	<span>with the span inline with the text</span>.
</div>
```

This div has its own line.
This shows on a second line, with the span inline with the text.

### Structure and Page Information

When you create an HTML project in Replit, there is a bunch of HTML in `index.html`. You will not need to write these tags yourself, but here’s what they mean in case you were curious.

- **List: Structure and Page Information tags**
    
    [Read more on MDN about page metadata](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)
    
    - `<!DOCTYPE html>` isn’t actually an element. It goes at the top of a file to say that it’s HTML.
    - `<html>` is the ‘root element’ of an HTML document. All of the other elements should be inside it.
    - `<body>` is where all the page content should go - everything you see on the page.
    - `<head>` is hidden metadata. It’s data about the webpage that doesn’t show up on the screen.
    - `<title>` is the title of the page. It’s what shows in search results and in the browser tab.
    - `<meta>` is for various other metadata about the page. There’s lots of types, which you can [read about on MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta).

### Multim**edia and Embedding**

There are lots of tags for including media on a webpage.

- **List: Media tags**
[Read more on MDN about multimedia and embedding](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding)
    
    `<iframe>` is for embedding external site content onto a page
    
    `<audio>` for an audio recording
    
    `<video>` for a video recording
    
    `<canvas>` is an element where you can draw shapes programmatically. Used for animations and games!
    
    `<object>` is an element for embedded content, like a pdf or a video.
    

### Forms

There is a whole set of HTML tags that are all about forms. We’ll focus on them in Week 3, but here’s the list as a preview:

- List: Form tags
MDN has [several pages on Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms). We’ll learn more in Week 3.
    
    `<form>` is for creating a form and grouping all the elements inside as part of the form
    
    `<input>` represents an input. There are [lots of different types of inputs](https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types)!
    
    `<button>` is a button, like a Next or Submit button.
    
    `<select>` shows a dropdown
    
    `<option>` is for the items in a select dropdown, like `<li>` is for items in a list
    

## MDN Element Reference

Those are the core elements you’ll encounter.

For the full listing of HTML Elements, check out the [MDN Elements Reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element).

---

*Happy Elementing!*