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
  <meta property = "og:image" content = "Dummy Website"/>
  <title> Document title goes here </title>
  <link rel = "stylesheet" href = "./styles.css"/>
</head>
```
Your site's metadata, contained in `meta` elements, has details about things like character encoding, how social medias should preview your link. 

**1. What is this page called?**

**Ans :** Contained in the `<title>` element. This determines the name that appears on your tab window.

**2. What is this page about?**

**Ans :** Contained in the `<meta name = "viewport" content = "..."/>` element. It provides a short summary of the page. Google shows this text under the main link in search results. 

**3. Where to obtain the syles from?**

**Ans :** Contained in the `<link rel = "stylesheet" href = "..."/>` element. This is to link your page to the external stylesheet.

**4. How should this look on social media?**

**Ans :** Contained in the `<meta property = "og:image" content = "..."/>` element. If you text a link to a friend, or post it on any social media - this metadata tells the app which image and title to show in the preview box.

#### **Body Tag -**
Where all the contents go in.

```html
<body>
  <h1> I am a Main Title </h1>
  <p> Example of a Paragraph Text </p>
</body>
```

**Conclusion :** Using a boilerplate helps you avoid common structural mistakes. It ensures that your webpage works well across different browsers, and you can customize your boilerplate according to you. As you gain experience, you might add your own `<meta>` tags or some other elements in your custom boilerplate.
