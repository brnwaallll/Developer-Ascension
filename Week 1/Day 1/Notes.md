# **Day 1 - Introduction to Responsive Web Designing**

### **Brief Introduction -** 

• **HTML (Hypertext Markup Language)** is used to build the structure and content of a webpage.

• **CSS (Cascading Style Sheets)** is used to design the webpage.

• **JS (JavaScript)** is used to add interactivity to a webpage.

## About HTML

**Q. What does HTML do on a webpage?**

**Ans:** When you visit a website and come across contents like paragraphs, images, links, videos, all sorts of headings - That is **HTML.**

**HTML** has two kinds of elements - Void & Non Void. Here, **Void** elements being those who come with a closing tag that looks like `</end>` whereas **Non Void** elements being those who don't require a closing tag.

## Elements

### **1. Heading Element -** 

• HTML offers a range of headings from `<h1>` being the most important to `<h6>` being the least

• Heading element is a non-void element hence it will require closing tag like so : `<h1>` `</h1>`

### **2. Paragraph Element -**

• The name explains itself. It is also a non-void element thus it would also require a closing tag : `<p>` `</p>`

### **3. Image Element -**

• Image element is used to add images to the webpage and is a void element hence it does not require any closing tags.

• However, in many codes you may find closing tags such as `<img>` `<img/>` which is only written for a prettier format as preferred by coders, however there is no requirement as the function `<img/>` has no effect.

## Attributes

**Q. What are attributes?**

**Ans:** Attribute is a value placed inside the opening tag of HTML. It either provides additional information about the element or decides how the element should behave. Here's the basic syntax - 

`<element attribute = "value">` `</element>`

### **1. href Attribute -** 
Specifies the URL of the link.

### **2. target Attribute -**
Specifies where to open the link.

Example - `<a href = "https://github.com/" target = "_blank">Visit GitHub</a>`

Output - <a href = "https://github.com/" target = "_blank">Visit GitHub</a>

**NOTE :** Here, `target="_blank"` enables the link to open in a new browser tab. There are more commands for target attribute as well.
