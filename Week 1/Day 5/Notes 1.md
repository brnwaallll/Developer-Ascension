# **Optimizing Media Assets -**

**Q. What should you consider when using media, like images, on a web page?**

**Ans :** There are three things to consider - the **size**, the **format**, and the **compression.**

## 1. Size

**Ans -** Images are often styled to display at a specific size. For example, an image might be styled to display at a 640x480 resolution, where 640 is the width and 480 is the height, in pixels.

• When preparing an image, scale it to match the size it will actually be displayed at.

• Serving a 1920x1080 image but styling it much smaller forces users to download unnecessary data.

**NOTE :** A smaller resolution results in a smaller file size.

## 2. Format

**Ans :** Two of the most common file formats are `PNG` and `JPG`, but they are no longer the most ideal formats for serving images.

• Unless support for older browsers is required, more optimized formats like `WEBP` or `AVIF` should be considered instead.

## 3. Compression

**Ans -** Compression algorithms can be run on images to reduce file size, but not all formats behave the same way.

### • Lossless Compression
Tools like `pngcrush` work well for lossless formats like PNG, which can be compressed without any quality loss, since the original data can be perfectly reconstructed.

### • Lossy Compression
JPG uses lossy compression - each time a JPG is re-saved or re-compressed, some image data is permanently discarded, resulting in degraded quality.

---

All three of these - size, format, and compression - should be kept in mind when selecting and preparing images for a web page.

## Quick Recap

• Scale images to match their rendered size on the page - not larger, not smaller.

• Prefer `WEBP` or `AVIF` over `PNG`/`JPG` when older browser support isn't a concern.

• Lossless compression (e.g. PNG) preserves quality; lossy compression (e.g. JPG) degrades it with every re-save.
