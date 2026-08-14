# **IDs and Classes -**
**Q. What are IDs and Classes?**

**Ans :** The `id` attribute adds a unique identifier to an HTML element. These are unique i.e. `id` names can only be used once and cannot contain any spaces.

```html
<h1 id = "title">Heading</h1>
<h2 id = "subtitle">Sub-Heading</h2>
```
We already know that `<h1>` is the most important heading, however we can still give `<h1>` a unique identifier. IDs are mainly referenced within your JavaScript or CSS.

**Here are some examples :**
### • index.html 
```html
<!DOCTYPE html>
<html lang = "en">
  <head>
    <meta charset = "UTF-8"/>
    <meta
      name = "viewport"
      content = "width=device-width, initial scale = 1.0"/>
    <title>Review Page Example</title>
    <link rel = "stylesheet" href = "./styles.css+"/>
  </head>
  <body>
    <h1 id = "title">Review Page</h1>
  </body>
</html>
```
### • styles.css
```css
#title {
  color : red;
}
```
