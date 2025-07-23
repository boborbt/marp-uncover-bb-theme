---
marp: true
theme: uncover-bb
---

# <!-- fit --> Hero title (with emoji 🦸)

---

# Header level 1
## Header level 2
### Header level 3
#### Header level 4


---

# List example

- list item 1
- list itme 2

# Numbered list example

1. list item 1
2. list item 2

---

# Quotations

<div class="grid-container" style="grid-template-columns:1fr 1fr">

<div class="column-1">

> Quotation example with reference attribution. The reference can be added using the `<qref>` tag.

<qref>Author: anonymous</qref>

</div>

<div class="column-2">

```markdown

> Quotation example with reference attribution
<qref>Author: anonymous</qref>

```

</div>

</div>



---

# Two columns layout

<div class="grid-container" style="grid-template-columns:1fr 1fr">

<div class="column-1">
    Two columns layout can be activated using the html markup on the right.
</div>

<div class="column-2">

```html
<div class="grid-container" style="grid-template-columns:1fr 1fr">

    <div class="column-1">
        content of the first column
    </div>

    <div class="column-2">
        content of the second column
    </div>
</div>
```
</div>

</div>

</div>

</div>

---

# Bibliographic references


<div class="grid-container" style="grid-template-columns:1fr 1fr">

<div class="column-1">


Bibliographic labels appears as superscripts<span class="noteref">1</span>.

<div class="ref">
<span class="label">1</span>
<span class="author">Roberto Esposito</span>
<span class="title">The corresponding bibliographic entry is displayed in the footnote.<span>
<span class="year">
2023
</span>
</div>

</div>

<div class="column-2">

```html

Bibliographic labels appears as superscripts<span class="noteref">2</span>.

<div class="ref">
<label>1</span>
<span class="author">Roberto Esposito</span>
<span class="title">The corresponding bibliographic entry is displayed in the footnote.<span>
<span class="year">
2023
</span>
</div>

```

</div>

</div>

---

# Note boxes

A note box can be created using the following syntax:

```html

<div class="note">
> # Header note can be set using `#`
> A note can be created using the `<div class="note">text
</div>` tag.

```

**Note**: the quotation mark `>` is needed, and the `#` is used to create a header inside the note.

<div class="note"> 

> # Header note can be set using `#`
> A note can be created using the `<div class="note">text</div>`

</div>

---

# HTML tags and symbols

A few special tags are available to highlight some concepts.

- A negative/positive "example" can be shown using the `<neg></neg>` <neg></neg> and the `<pos></pos>` <pos></pos> tags.
- <box>A boxed text</box> can be created using the `<box>text</box>` tag.
- A check mark <chk></chk> can be added using the `<chk></chk>` tag.
- A cross <crs></crs> can be added using the `<crs></crs>` tag.





