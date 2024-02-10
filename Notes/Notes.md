# Key Points for HTML.

## Basics of HTML

**HTML** stands for **HyperText Markup Language**.

+ **HyperText**: This refers to _text that contains links to other texts_. In the context of the web, it means text that is linked to other documents or resources, allowing for non-linear navigation. You can click on hyperlinks to jump from one document to another.

+ **Markup**: Markup refers to the set of symbols or codes embedded in a document to give instructions on how the document should be displayed or processed. In the case of HTML, these codes are _used to structure and format text, add images, create links, and more_.

So, HTML is a language for creating structured documents with hyperlinks. It's the standard markup language for documents designed to be displayed in a web browser.

----------------------------------------------------
### Example:

```html
<!DOCTYPE html>
<html>
<head>
    <title>My First HTML Page</title>
</head>
<body>

    <h1>Hello, World!</h1>

    <p>This is a paragraph of text.</p>

    <a href="https://www.example.com">Visit Example.com</a>

</body>
</html>
```

```html
<!DOCTYPE html>: Defines the document type and version of HTML (in this case, HTML5).
<html>: The root element of an HTML document.
<head>: Contains meta-information about the HTML document, such as the title.
<title>: Sets the title of the HTML document, which appears in the browser's title bar.
<body>: Contains the content of the HTML document.
<h1>: Defines a top-level heading.
<p>: Defines a paragraph.
<a>: Defines a hyperlink, where href is the attribute specifying the destination URL.
```

>Think of HTML as the blueprint or structure of a building. The blueprint contains instructions on how different parts of the building should be arranged and connected. Each element in HTML (like headings, paragraphs, links) is like a different component of the building. Hyperlinks act as doors or pathways connecting different parts of the building or even leading to other buildings (web pages). So, HTML is essentially the language that structures and connects different pieces of content on the web, creating a cohesive and navigable experience for users.

### Elements
![image](https://github.com/hiMadhusudan/HTML-Codes-and-Notes/assets/76695160/26529da8-e5f0-448d-9059-39ff542d5f71)

> [!NOTE]
> HTML is case-insensitive, still, we should write tags and attributes in lowercase.  
> Some attributes' value is case-sensitive.  
> HTML forgives us if we skip the closing tag for some HTML elements, still, we should use the closing tag.  

-----------------------------------------------------------------------------------------------------------------

## Document Structure

```html
<!DOCTYPE html>
<html lang="en"> 
  <head>
    <meta charset="utf-8" />
    <title>Machine Learning Workshop</title>
    <meta name="viewport" content="width=device-width" />
  </head>
  <body>

  </body>
</html>
```

![image](https://github.com/hiMadhusudan/HTML-Codes-and-Notes/assets/76695160/b423049a-8510-4117-9c5c-d8b6915cd105)
