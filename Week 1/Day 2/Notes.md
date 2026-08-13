# **HTML Boilerplate**
**Q. What is a HTML Boilerplate?**

**Ans -** It is the foundation, the HTML Boilerplate contains all the basic structure and essential elements that every HTML document needs. It saves you time and make sure that your pages are set up properly.

## **Let's breakdown the Boilerplate.**

### **1.** Doctype Declaration.
It tells the browser which version of HTML you are using.

```html
<!DOCTYPE html>
```
### **2.** HTML Tag.
This tag contains all the essentials and important elements. This is also where you set the language for your page.

```html
<!DOCTYPE html>
<html lang = "en">
  <!--All other elements go inside here-->
</html>
```
### **3.** Head & Body Tag.
Inside the HTML tag, you will find two main sections.

```html
<!DOCTYPE html>
<html lang = "en">
  <head>
    <!--Important metadata goes here-->
  </head>
  <body>
    <!--Headings, paragraphs, images, etc. go inside here-->
  </body>
</html>
```
#### **Head Tag -** 
Contains all the metadata. Metadata is the "actual" content. Metadata is the ***hidden*** information, about the website that the normal visitors do not see on the page, but the computer **needs** to read it.

```html
<head>
  <meta charset = "UTF-8"/>
  <meta name = "viewport" content = "width = device-width, initial scale = 1.0"/>
  <title> Document title goes here </title>
  <link rel = "stylesheet" href = "./styles.css"/>
</head>
```
