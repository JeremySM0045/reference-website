# reference-website
1. Naming convention for all filenames, paths and folders
- The naming conventions for all filenames should be lowercase, no spaces and dashes are fine. Folder 
naming convention should be similar to filenames. For paths, the folders, assets and files should be
inside the root folder so they can be easily linked to any .html files `index.html` 

2. Best practices for commit messages
- When it comes to best practices, there's a few things to consider. Firstly, you want to be specific about what the
commitment includes. the commit should be consistant and include as much detail about the changes made, rather than 
simply writing `updated index.html`. For example, when I push for this question I would write 
`completed question 2 regarding best practices for commit messages.` Secondly, if you were to be working on a code with a 
team, you want to make sure to properly identify yourself, your changes as well as any comments you'd like the others to see.
This will make your changes a great deal easier to read and understand. Lastly, make sure to keep your commits diverse. They 
don't need to be particularly unique, but distinct enough to be told apart. 

3. What is HTML?
- The term HTML itself stands for Hyper Text Markup Language. This
scripting language's purpose lies in the ability to describe, define and isolate elements found on any and all web pages. The tags that make up this language are mainly used to identify the 
purpose of an element, such as the `<p></p>` tags, that define the
start and finish of a paragraph element, or more involved tags like
`<nav></nav>` that helps define a functional navigation system. HTML does not involve anything to do with functionalty and appearance, that would rather be with `CSS and JS`.

4. Proper syntax for HTML tags
- When writing proper HTML tags, there's a few rules to keep in mind when regarding the syntax. Firstly, always type your tags in lowercase, with the only common exception to this being `<!DOCTYPE>`. Secondly, to every opening tag there is a closing tag, one that includes a `/` along with its tag; Ex: `<h1></h1>`. Forgeting these can cause minor or major problems to the containement of elements depending on the tag. Lastly, when using heading tags, make sure to work from `h1-h6` in that order, though only introduce new heading types if absolutely necessary. The same applies to using `section`, `article` and `div`.

5. Explain or demonstrate commonly used html tags/elements:
- `<h1>-<h6>` h1 is used once for the main heading. h2 for section headings, and h3-h6 for sub-headings.
- `<p>` is used to define an section of text as a paragrah element.
- `<ul>, <ol>, <dl>` is used to define (3) different types of lists. `ul` is used for unordered lists that include bullet-points, `ol` is used for ordered lists that are numbered, and finally `dl` is for a description list which include indented descriptors to the item in question.
- `<a>` refers is to used to define hyperlinks found within the page.
- `<img>` refers to imported elements that are images in jpg, svg, png and other file type.
- `<figure>` is used to define self-contained content. a `<figcaption>` is a caption for the figure content.
- `<q>` is used to define a short quotation.
- `<blockquote>` is used to define a section that is quoted from another source.
- `<cite>` is used to define the title of a work.
- `<em>`is used to place emphasis on a text.
- `<strong>` is used to define important text. Both `<em>` and `<strong>` are commonly used to improve accessibility.
- `<b>` is used to make text bold.
- `<i>`is used to define a shift in tone or mood for a part in a text. the content will be displayed in `italic`
- `<small>` is used to define smaller text that the rest of the text.

6. Explain block Elements and also explain the list of block elements and why they are used from below 
- As a summary, block elements are elements that follow the base block format. These inlude always starting on a new line, automatically adding margin between itself and other elements. In essence, a block element ''blocks'' itself off from the other elements. some examples are:
- `<html>` is used to define the root of the HTML document. It also groups up all the code from start to end. 
- `<head>` is used to define the section that contains all the metadata and information for a document.
- `<body>` is used to define the document's body.
- `<header>` is used to defined the header for the document or section.
- `<nav>` is used to define the section with the navigation links.
- `<main>` is used to define the main content of a document. 
- `<section>` is used to define a section within a document.
- `<article>` is used to define an article within a document.
- `<div>` is also used to define a section in a document, though typically within an existing `<section>`.
- `<aside>` is used to define content that is labeled as being aside the page content. Usually where adverts are located.
- `<footer>` is used to define a footer for a document or section.
- `<span>` is used to define a section in a document, much like `<section>` and `<div>`.
- `<small>` is used to define smaller text within a text.

7. Explain why accessibility is important and also explain the accessibility properties
- when it comes to accessibility, it is incredibly important because of the ease of access it provides for anyone that might have minor or major visual, auditory and/or sensory disabilities. By including accessibility properties, you make the user experience that much profound.
- `landmark roles` are roles provided to identify different key sections that the web reader might want to highlight, such examples include `banner``navigation``main` and so forth. 
- `aria-labels` are descriptors that can be read by screen readers to describe and informe the user about what they are interacting with. This is usually for images, landmarks and interactive elements like hyperlinks. The text itself will not be visible on screen.
- `image alternative texts` or simply `alt` work in the same way as aria-labels, as there purpose is to describe and define images for those that might have impaired vision. Much like aria-label, their text will not be visible on screen. 

8. What is CSS and how can we implement CSS to our html file
- In essence, CSS works in tandum with HTML, whereas HTML deals with formating and labeling, CSS's main purpose is visual changes to the web page. Anything from positioning, orientation, color, typeface, margins and much more. 
- To link your HTML to your CSS code, you must first create a `style.css` file within a `CSS Folder`, then write the following line within the `<head>` of your HTML:
`<link rel="stylesheet" href="css/style.css">`. This will effectively make sure any code writing in your style.css will influence your index.html code. 

9. What is the difference between CSS property and value
- When coding CSS, the `property` and `value` make up the 2 components of a declaration. the `property` refers to what you are looking to edit, some example include `color`, `width` , `margin`, and so forth. The `value` refers to the increment you want to edit the property, with there being different increment types depending on the situation. some cases use `em`, `rem`, `px`, `%`, and so forth. Example: `h1 {font-size: 120px;}`
