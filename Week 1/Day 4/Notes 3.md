# **HTML Audio and Video Elements -**

**Q. What are the audio and video elements used for?**

**Ans :** The `audio` and `video` elements allow sound and video content to be added to HTML documents.

• The `audio` element supports popular audio formats like mp3, wav, and ogg.

• The `video` element supports mp4, ogg, and webm formats.

## The audio Element

To include audio on a page, use the `audio` element with the `src` attribute pointing to the audio file.

```html
<audio src="cruising-for-a-musing.mp3"></audio>
```

**NOTE :** On its own, nothing visible shows up on the page for this. To see an actual player, the `controls` attribute needs to be added.

### **1. controls Attribute -**
Enables users to manage playback, including pausing or resuming. It is a boolean attribute - if omitted, no controls will be shown.

```html
<audio src="cruising-for-a-musing.mp3" controls></audio>
```

**NOTE :** Some browsers, such as Safari, may not display a volume control by default even when `controls` is present.

### **2. loop Attribute -**
A boolean attribute that makes the audio replay continuously once it finishes.

```html
<audio src="cant-stay-down.mp3" loop controls></audio>
```

### **3. muted Attribute -**
A boolean attribute that starts the audio in a muted state.

```html
<audio src="cant-stay-down.mp3" loop controls muted></audio>
```

## Multiple Sources

Browser support varies across audio file types. To account for this, `source` elements can be nested inside `audio`, and the browser will pick the first one it understands.

```html
<audio controls>
  <source src="audio.ogg" type="audio/ogg" />
  <source src="audio.wav" type="audio/wav" />
  <source src="audio.mp3" type="audio/mpeg" />
</audio>
```

**NOTE :** The browser starts with the first source in the list and moves down if it can't play that type.

## The video Element

All the attributes covered above (`controls`, `loop`, `muted`) are also supported in the `video` element. `video` additionally supports -

### **4. autoplay Attribute -**
Makes the video begin playing automatically.

### **5. poster Attribute -**
Unique to the `video` element - not available for `audio`. Displays an image while the video is downloading.

```html
<video
  src="big_buck_bunny_720p_surround.mp4"
  loop
  controls
  muted
  poster="title_anouncement.jpg"
  width="400"
></video>
```

Just like `audio`, `video` also supports multiple `source` elements to provide the same video in different formats -

```html
<video controls width="400" poster="title_anouncement.jpg">
  <source src="big_buck_bunny_720p_surround.mp4" type="video/mp4" />
  <source src="big_buck_bunny_720p_surround.webm" type="video/webm" />
  Your browser does not support the video tag.
</video>
```

## Quick Recap

• `audio` and `video` need a `src`, or nested `source` elements, to know what file to play.

• `controls`, `loop`, and `muted` are boolean attributes shared by both elements.

• `poster` is unique to `video` - it displays an image before the video loads.

• Multiple `source` elements let the browser pick the first format it can play.
