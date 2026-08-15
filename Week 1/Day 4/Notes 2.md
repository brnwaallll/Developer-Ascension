# **Open Graph Tags and SEO -**

**Q. What is the Open Graph protocol?**

**Ans :** The **Open Graph (OG) protocol** enables control over how a website's content appears across social media platforms such as Facebook and LinkedIn. These properties are set through a collection of `meta` elements inside the HTML `head` section.

## The Key OG Properties

### **1. og:title -**
Specifies the title that gets displayed when the content is shared on social media.

```html
<meta content="freeCodeCamp.org" property="og:title" />
```

### **2. og:type -**
Represents the type of content being shared - examples include articles, websites, videos, or music.

```html
<meta property="og:type" content="website" />
```

### **3. og:image -**
Points to the image shown alongside the shared content.

```html
<meta
  content="https://cdn.freecodecamp.org/platform/universal/fcc_meta_1920X1080-indigo.png"
  property="og:image"
/>
```

**NOTE :** Images should be high quality with good dimensions. Facebook's developer documentation recommends using images at least 1200 by 630 pixels for high resolution devices, with 600 by 315 pixels as the minimum.

### **4. og:url -**
Specifies the canonical URL of the page.

```html
<meta property="og:url" content="https://www.freecodecamp.org" />
```

---
There are more OG properties available too, such as `description`, `audio`, `video`, and `locale` - however `url`, `image`, `type`, and `title` are the most important ones to include.

---

## How Does This Affect SEO?

**Ans -** When content is shared on social media, well-crafted OG properties can enhance how it appears in users' feeds. This can lead to a higher click-through rate, which in turn can signal to search engines that the content is relevant and engaging.

## Quick Recap

• OG properties are set through `meta` elements, using a `property` attribute instead of `name`.

• The four essential ones are `og:title`, `og:type`, `og:image`, and `og:url`.

• They control how content looks when shared on social platforms, which indirectly helps SEO through better engagement.
