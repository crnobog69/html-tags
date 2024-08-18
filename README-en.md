# HTML Tags - Quick Overview

This README provides a brief description of the following HTML tags:

## 1. `<abbr>`
Used for marking abbreviations or acronyms.
```html
<abbr title="World Health Organization">WHO</abbr>
```

## 2. `<code>`
Used for displaying code within text.
```html
<p>Here’s how to use a `for` loop in JavaScript:</p>
<code>for(let i = 0; i < 5; i++) { console.log(i); }</code>
```

## 3. `<kbd>`
Indicates keyboard input.
```html
<p>Press <kbd>Ctrl</kbd> + <kbd>C</kbd> to copy text.</p>
```

## 4. `<datalist>` and `<option>`
Used to create dropdown lists in text input fields.
```html
<input list="browsers" name="browser">
<datalist id="browsers">
  <option value="Chrome">
  <option value="Firefox">
  <option value="Safari">
</datalist>
```

## 5. `<dialog>`
Used to create dialog boxes.
```html
<dialog id="myDialog">This is a dialog box.</dialog>
<button onclick="document.getElementById('myDialog').showModal()">Open Dialog</button>
```

## 6. `<time>`
Represents time or date.
```html
<time datetime="2024-08-18">August 18, 2024</time>
```

## 7. `<ruby>`, `<rt>`, and `<rp>`
Used to display annotations on text, often in Asian languages.
```html
<ruby>漢字<rt>かんじ</rt></ruby>
```

## 8. `<progress>`
Indicates the progress of a task.
```html
<progress value="70" max="100">70%</progress>
```

## 9. `<meter>`
Used to display measurement data within a range.
```html
<meter value="0.7" min="0" max="1">70%</meter>
```

## 10. `<fieldset>` and `<legend>`
Groups form elements and adds a title to the group.
```html
<fieldset>
  <legend>Personal Information</legend>
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">
</fieldset>
```

## Conclusion
This is a quick overview of basic HTML tags that can be used for various purposes in web development. For more information, you can refer to the official documentation.
