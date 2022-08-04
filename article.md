#  Intro To HTML
  
---
  
##  What is HTML
  
HTML, short for Hyper Text Markup Language, is a standard markup language (not to be confused with programming language) used for webpage creation. HTML allows the creation and structure of sections, paragraphs and links and also allows one to add images, videos, and gifs, and also assign different tags to different attributes or elements in your code.
  
HTML has a lot of use cases. Eg;
  
- Web development
- Internet navigation
- Web documentation
  
##  Parts of an element
  
  
Every element can be divided in to 3 main parts. The 3 main parts of an element are:
  
- Opening tag - used to state where the element starts to take effect. The tag is wrapped with opening and closing angled brackets. For example, use the start tag `<p>` to create a paraph.
  
- Content - the output that other users see
  
- Closing tag - used to state where the element stops taking effect. Like the opening tag but with a forward slash before the element name. For example, `<p>`  to end a paragraph.
  
The combination of these elements will create the HTML element:
  
> `<p>`This is how you add a paragraph in HTML.`<p>`
  
Another critical part of an HTML element is its attribute, which has two sections - a name and attribute value. The name specifies what additional information the user wants to add while the value gives further specifications. Eg;
  
For example the style element adding the colour purple and font-family arial will look like this:
  
> `<p>``<p style="color:purple;font-family:arial">`This is how you add a paragraph in HTML.`</p>`
  
Another attribute, which is probably actually the most important for development and programming, is the HTML class. A class is a tag that can be assigned to an HTML element that can also be used to style that element. Multiple elements can be assigned to the same class. This is particularly helpful for styling multiple similar elements.
  
For example, we will use the same style for a heading `<h1>` and a paragraph `<p>`.  The style includes background colour, text colour, border, margin, and padding under the same class .important. To achieve the same style between `<h1>` and `<p>`, add `class="important"` after each opening tag.
  
> `<html>`
> `<head>`
>  `<style>`
>  `.important {`
>  `background-color: blue;`
>  `text-color: white;`
>  `border: 2px solid black;`
>  `margin: 2px;`
>  `padding: rpx;`
>  `}`
>  `</style>`
>  `</head>`
>  `<body>`
>  
>
>
> `<h1 class="important">This is a heading</h1>`
> `<p class="important">This is a paragraph.</p>`
> `</body>`
> `</html>`
  
Most elements have an opening tag and a closing tag, but some elements do not need a closing tag to work, such as empty elements. However, it does not have a content nor an end tag. Eg;
  
> `<img src=".." alt="Image">`
  
This image tag has two attributes - an src attribute, the image path, and an alt attribute, the descriptive text. However, it does not have content nor an end tag.
  
Lastly, every HTML document must start with a <!DOCTYPE> declaration to inform the web browser about the document type. With HTML5, the doctype HTML public declaration will be:
  
> `<!DOCTYPE html>`
  
  
  
  
  
  
  