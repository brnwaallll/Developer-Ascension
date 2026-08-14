# **Content Division and its Elements -**
**Q. What are div elements and when should you use them?**

**Ans -** The `<div>` element is mainly used to segregate a section that would share CSS styles. Thus mainly it is used for styling purposes.

```html
<div>
  <p>Example paragraph here.</p>
  <p>Then here's the second paragraph, which is grouped together with first paragraph.</p>
</div>
```
**Output :**
```text
Example paragraph here.
Then here's the second paragraph, which is grouped together with first paragraph.
```
**NOTE :** Even though the `<div>` element is widely used, you need to make sure that you don't overuse it. There are many other such elements that serve the purpose better during segregation or grouping. This is where the concept of **Semantic HTML** comes in.

## **Semantic HTML -**
**Semantic HTML** means using web tags that clearly describe their meaning to both the browser and the developer. When you use semantic tags, you are telling the computer ***what kind of content*** is inside them, not just how it should look.

### **1. The Analogy :**
• A `<div>` element is like a blank piece of paper.

• A `section` element is like a labelled chapter header.

### **2. Non-Semantic v/s Semantic Elements :**
• **Non Semantic (`<div>`,`<span>`) -** These elements say nothing about their content. A `<div>` is just an empty box. The browser doesn't know if it holds a menu, a blog post, or a footer.

• **Semantic (`<section>`, `<header>`, `<article>`, `<footer>`) -** These elements explicitly define their content.

### **3. Why Semantics Matter :**
• Cleaner code.

• Better SEO.

• Better accessibility for the disabled and the computer.

```html
<section>
  <h2>Heading</h2>
  <p>Here comes paragraph content</p>
  <ul>
    <li> Pointer 1</li>
    <li> Pointer 2</li>
    <li> Pointer 3</li>
  </ul>
</section>
```
**Output :**
```text
Heading
Here comes paragraph content
  • Pointer 1
  • Pointer 2
  • Pointer 3
```
