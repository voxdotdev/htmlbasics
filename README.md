# [Html Basics](https://www.theodinproject.com/lessons/foundations-introduction-to-html-and-css)


### HTML ELEMENT 
An HTML element consists of an opening tag, a closing tag, and the content within.

### HTML BOILERPLATE 
All HTML documents have the same basic structure or boilerplate that needs to be in place before anything useful can be done.

1. Create [folder html-boilerplate](./html-boilerplate/)
2. Within that folder create a new file and name it [index.html](./html-boilerplate/index.html).

### The DOCTYPE 
Every HTML page starts with a doctype declaration. The doctype’s purpose is to tell the browser what version of HTML it should use to render the document. The latest version of HTML is HTML5, and the doctype for that version is simply `<!DOCTYPE html>`

### HTML Element
After we declare the doctype, we need to provide an `<html>` element. This is what’s known as the root element of the document, meaning that every other element in the document will be a descendant of it.

### Head Element
The `<head>` element is where we put important meta-information about our webpages, and stuff required for our webpages to render correctly in the browser. Inside the `<head>`, we should not use any element that displays content on the webpage.

### Title Element

Another element we should always include in the head of an HTML document is the title element:

`<title>My First Webpage</title>`