## HTMl Structure

HTML5, or HyperText Markup Language 5, is the latest version of the HTML standard, which is a markup language used for structuring content on the web. HTML provides a set of elements and attributes that web developers use to create and design web pages. It is the foundation in which you are able to create websites. 

#### Example of basic structure:

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
  </head>
  <body>
    <h1>Hello, world!</h1>
  </body>
</html>
```

It is important to note that HTML is often used in conjunction with CSS (Cascading Style Sheets) for styling and JavaScript for dynamic behaviour, forming the core technologies for building websites and web applications.  

## Semantics of Basic HTML Structure

`<!doctype html>` - The "doctype" declaration at the beggining of a HTML document notifies the web browser that it is written in HTML5. This ensures that the browser displays the content correctly and follows the most up to date web standards.

`<head>` - This element contains information about the document itself and is not displayed onto the web page - for example like what language it is in, or how to display the information correctly. This is known as metadata which is used to help browsers, search engines or web services understand and process the page.

`<html lang = "en">` - This tag specifies the primary language of the content inside of the HTML document. 

`<meta charset="utf-8">` - This tag specifies the character encoding used in the document. In essence, it is telling the browser how to read and display the text on the webpage correctly.

`<title>` - This simply sets the title of the webpage - this is what you would see on the browser tag.

`<meta name="viewport" content="width=device-width, initial-scale=1">` - This tag assists with the scaling aspects from each device. Whether that is a laptop, tablet or mobile phone; you want to make sure it looks good for every user.

`<body>` -Unlike the the head; this element contains all information that is to be displayed directly onto the page. This can include things such as text, images, videos, links or other various elements.

`<h1>` - This tag is used to create the main heading or title for a webpage.

Learn more on meta tags here https://www.w3schools.com/tags/tag_meta.asp

## HTML Resources

HTML attributes provide additional information about HTML elements and are used to modify or customise the behaviour of those elements. They are always included in the opening tag of an HTML element and consist of a name and a value, separated by an equals sign. The value is enclosed in double or single quotes.

#### Here's a simple example:

```html
<a href="https://www.example.com" target="_blank">Visit Example.com</a>
```

In this anchor (`<a>`) element, the `href` and `target` attributes are used. The `href` attribute specifies the URL that the link points to, and the `target` attribute determines how the linked resource will be displayed (in this case, it opens in a new browser window or tab).

#### Some common HTML attributes include:

* `id`: Specifies a unique identifier for an element.
* `class`: Assigns one or more class names to an element, allowing CSS styles to be applied.
* `src`: Specifies the source URL of embedded content, such as images or scripts.
* `alt`: Provides alternative text for images, which is displayed if the image cannot be loaded.
* `style`: Defines inline CSS styles for an element.
* `width` and `height`: Set the width and height of elements like images and tables.
* `disabled`: Disables user interaction with an input element or button.
* `placeholder`: Displays a short hint in an input field before a user enters a value.
* `value`: Sets the initial value for form elements like input fields.

HTML attributes vary depending on the type of element they are applied to, and different elements may support different attributes. 

#### HTML Reference:

`<!DOCTYPE html>` - Declares the HTML document type and version.

`<html>` - The root element of an HTML document.

`<head>` - Contains meta-information about the HTML document, such as title, character set, styles, and scripts.

`<title>` - Sets the title of the HTML document, displayed in the browser's title bar or tab.

`<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">` - Responsive meta tag to ensure proper rendering and touch zooming for all devices

`<body>` - Contains the content of the HTML document, including text, images, links, and other elements.

`<h1>, <h2>, ..., <h6>` - Defines headings of different levels, with `<h1>` being the highest and `<h6>` the lowest.

`<p>` - Defines a paragraph.

`<a>` - Creates hyperlinks to other web pages, files, or locations within the same document.

`<img>` - Embeds an image in the document.

`<ul>, <ol>, <li>` - Defines unordered (bulleted) and ordered (numbered) lists and list items.

`<div>` - A container that groups and styles other HTML elements. Often used for layout purposes.

`<span>`- A inline container used to apply styles or scripting to a specific portion of text.

`<br>` - Inserts a line break within text.

`<hr>` - Defines a horizontal line, often used to separate content.

`<form>` - Creates a form to collect user input, which can include text fields, buttons, checkboxes, and more.

`<input>` - Defines an input field within a form, such as text, password, checkbox, radio button, etc.

`<label>` - Associates a label with a form element, improving accessibility and user experience.

`<textarea>` - Creates a multiline text input field within a form.

`<select>, <option>` - Defines a dropdown list within a form and its selectable options.