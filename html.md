[:house: < README](./README.md)

---

# HTML

Markdown allows raw HTML passthrough.
You can insert HTML directly into a .md file when Markdown syntax is insufficient.
- Inline HTML works inside Markdown text
- Block-level HTML must be uninterrupted and left-aligned
- Markdown is ignored inside HTML blocks
- Unsafe tags may be stripped by the renderer

Use HTML as an escape hatch, not a replacement for Markdown.

---

## Inline HTML

```html
This is inline <strong>bold</strong> and <span style="color:red;">red</span> inline HTML.
```
This is inline <strong>bold</strong> and <span style="color:red;">red</span> inline HTML.

## Block HTML

```html
<div style="margin: 1em 0; padding: 1em; border: 1px solid #ddd; border-radius: 6px;">
  <h3>📚 Useful Resources</h3>
  <p>
    This section demonstrates a <strong>long HTML snippet</strong> embedded inside a
    Markdown file. All links open in a new tab and include emojis in their descriptions.
  </p>
  <ul>
    <li>
      <a href="https://example.com/docs"
         target="_blank"
         rel="noopener noreferrer">
        🔗 Project Documentation
      </a>
      <br />
      <small>Official documentation and usage guides</small>
    </li>
    <li>
      <a href="https://github.com"
         target="_blank"
         rel="noopener noreferrer">
        🐙 GitHub Repository
      </a>
      <br />
      <small>Source code, issues, and pull requests</small>
    </li>
    <li>
      <a href="https://stackoverflow.com"
         target="_blank"
         rel="noopener noreferrer">
        ❓ Stack Overflow
      </a>
      <br />
      <small>Community-driven questions and answers</small>
    </li>
  </ul>
  <p style="margin-top: 1em;">
    ⚠️ <strong>Note:</strong>
    All links use
    <code>target="_blank"</code>
    and
    <code>rel="noopener noreferrer"</code>
    to ensure safe behavior when opening new tabs.
  </p>
</div>
```

<div style="margin: 1em 0; padding: 1em; border: 1px solid #ddd; border-radius: 6px;">
  <h3>📚 Useful Resources</h3>
  <p>
    This section demonstrates a <strong>long HTML snippet</strong> embedded inside a
    Markdown file. All links open in a new tab and include emojis in their descriptions.
  </p>
  <ul>
    <li>
      <a href="https://example.com/docs"
         target="_blank"
         rel="noopener noreferrer">
        🔗 Project Documentation
      </a>
      <br />
      <small>Official documentation and usage guides</small>
    </li>
    <li>
      <a href="https://github.com"
         target="_blank"
         rel="noopener noreferrer">
        🐙 GitHub Repository
      </a>
      <br />
      <small>Source code, issues, and pull requests</small>
    </li>
    <li>
      <a href="https://stackoverflow.com"
         target="_blank"
         rel="noopener noreferrer">
        ❓ Stack Overflow
      </a>
      <br />
      <small>Community-driven questions and answers</small>
    </li>
  </ul>
  <p style="margin-top: 1em;">
    ⚠️ <strong>Note:</strong>
    All links use
    <code>target="_blank"</code>
    and
    <code>rel="noopener noreferrer"</code>
    to ensure safe behavior when opening new tabs.
  </p>
</div>

---

## Media

For plain `.md` the only supported media type is images. For everything else, HTML is needed.

### Video

```html
<video controls>
  <source src="./media/file_example.mp4" type="video/mp4">
</video>
```

<video controls>
  <source src="./media/file_example.mp4" type="video/mp4">
</video>

Example from [file-examples.com](https://file-examples.com).

### Audio

```html
<audio controls>
  <source src="./media/file_example.mp3" type="audio/mp3">
</audio>
```

<audio controls>
  <source src="./media/file_example.mp3" type="audio/mp3">
</audio>

Example from [file-examples.com](https://file-examples.com).


### PDF

```html
<embed src="./media/sample.pdf" type="application/pdf" width="100%" height="400">
```

<embed src="./media/sample.pdf" type="application/pdf" width="100%" height="400">

Example from [pdfobject.com](https://pdfobject.com/pdf/sample.pdf).

### Embedded Web Content (if allowed)

```html
<iframe src="https://example.com"></iframe>
```

<iframe src="https://example.com"></iframe>


---

[:arrow_up: Back to Top](./html.md) 