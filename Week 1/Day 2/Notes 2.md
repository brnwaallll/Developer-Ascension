# **UTF- 8 Character Encoding**
**What is UTF-8?**

**Ans -** UTF-8 or UCS Transformation Format 8, is a standardized encoding widely used used on the web. Character encoding is the method used to store characters as data. All texts on webpage are sequence of characters stored as one or more bytes. One byte is a unit of data that consists of 8 bits, or binary digits.  

UTF-8 supports every character on the Unicode character set, and this includes all the characters and symbols from all writing system languages, and technical symbols. 
```html
<meta charset = "UTF-8"/>
```
### **Here's an example -**
By setting the character encoding to UTF-8, it will make sure that accented e will be displayed as `é` on the webpage.
```html
<!DOCTYPE html>
<html lang = "en">
  <head>
  <meta charset = "UTF-8"/>
  <meta name = "viewport" content = "width = device-width" initial scale = 1.0"/>
  <title> Examples of UTF-8 Character Encoding </title>
  </head>
  <body>
    <p>Café</p>
  </body>
</html>
```
