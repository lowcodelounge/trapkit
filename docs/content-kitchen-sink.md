---
layout: sidebar
prose: false
header: true
sidebar: content-nav.md
body-style: line-height-sans-4
---

# Content kitchen sink
Each of the code blocks below contains the Markdown format for each of the elements. Copy and paste them into your Markdown files to quickly add elements as you get to know the syntax.

## Block elements

### Headings

```
# Heading One
## Heading Two
### Heading Three
#### Heading Four
```
{: .padding-2 .bg-base-lightest .overflow-auto}

<details markdown="1" class="margin-top-2 margin-bottom-6">
<summary>How headings look rendered as HTML</summary>
# Heading One
## Heading Two
### Heading Three
#### Heading Four
</details>

### Paragraphs and Line Breaks

```
Two create a paragraph, add a space in between lines.

This is a separate paragraph.

To create a line break (or soft break)  
within a paragraph,  
add two spaces at the end of a line.

If you want something visible,<br>
use the HTML element.
```
{: .padding-2 .bg-base-lightest .overflow-auto}

<details markdown="1" class="margin-top-2 margin-bottom-6">
<summary>How paragraphs and line breaks look rendered as HTML</summary>
Two create a paragraph, add a space in between lines.

This is a separate paragraph.

To create a line break (or soft break)  
within a paragraph,  
add two spaces at the end of a line.

If you want something visible,<br>
use the HTML element.
</details>

### Lists

```
Unordered list:
- List item one
- List item two
- List item three

Ordered list:
1. List item one
1. List item two
1. List item three
```
{: .padding-2 .bg-base-lightest .overflow-auto}

Note that by using all 1s for ordered lists, you have to renumber your lists if you reorder the contents.

<details markdown="1" class="margin-top-2 margin-bottom-6">
<summary>How lists look rendered as HTML</summary>
Unordered list:
- List item one
- List item two
- List item three

Ordered list:
1. List item one
1. List item two
1. List item three
</details>

### Tables

```
| Document                    | Year |
|:----------------------------|-----:|
| Declaration of Independence | 1776 |
| Bill of Rights              | 1791 |
| Emancipation Proclamation   | 1863 |
{: .usa-table .width-tablet}
```
{: .padding-2 .bg-base-lightest .overflow-auto}

You can use a tool like [TableConvert](https://tableconvert.com/) to automatically generate the Markdown for you from a CSV file.

<details markdown="1" class="margin-top-2 margin-bottom-6">
<summary>How tables look rendered as HTML</summary>

| Document                    | Year |
|:----------------------------|-----:|
| Declaration of Independence | 1776 |
| Bill of Rights              | 1791 |
| Emancipation Proclamation   | 1863 |
{: .usa-table .width-tablet}
</details>

### Images

```
![This is the alt text for the image](path/to/image.jpg)
```
{: .padding-2 .bg-base-lightest .overflow-auto}

If you want more direct control over image size, you can alternatively use HTML:  


```
<img src="path/to/image.jpg" alt="This is the alt text for the image" width="640" height="480">
```
{: .padding-2 .bg-base-lightest .overflow-auto}

<details markdown="1" class="margin-top-2 margin-bottom-6">
<summary>How images look rendered as HTML</summary>
![This is the alt text for the image](../assets/img/workspace.jpg)
</details>

### Blockquote

```
> We hold these truths to be self-evident…
{: .border-left-1 .border-primary-light .padding-left-2 .padding-y-1 .font-body-lg .text-italic .margin-left-0}
```
{: .padding-2 .bg-base-lightest .overflow-auto}

Note the only default styling of the blockquote element is left margin spacing, so this example includes custom styling using design tokens and utility classes.


<details markdown="1" class="margin-top-2 margin-bottom-6">
<summary>How blockquotes look rendered as HTML</summary>
> We hold these truths to be self-evident…
{: .border-left-1 .border-primary-light .padding-left-2 .padding-y-1 .font-body-lg .text-italic .margin-left-0}
</details>

### Preformatted / Code

```
<button class="usa-button">Default</button>
```
{: .padding-2 .bg-base-lightest .overflow-auto}

How preformatted/code blocks look rendered as HTML 👆

### Horizontal Rule

```
---
```
{: .padding-2 .bg-base-lightest .overflow-auto}

<details markdown="1" class="margin-top-2 margin-bottom-6">
<summary>How horizontal rules look rendered as HTML</summary>
---
</details>

## Inline elements

### Link

```
[Visit Trap Kit homepage](https://pglevy.github.io/trapkit/){: .usa-link}
```
{: .padding-2 .bg-base-lightest .overflow-auto}

Note the `usa-link` class added here for better default hover and visited link behavior.

<details markdown="1" class="margin-top-2 margin-bottom-6">
<summary>How links look rendered as HTML</summary>
[Visit Trap Kit homepage](https://pglevy.github.io/trapkit/){: .usa-link}
</details>

### Emphasis

```
Make an *emphatic* statement.

Make an **emphatic** statement.
```
{: .padding-2 .bg-base-lightest .overflow-auto}

<details markdown="1" class="margin-top-2 margin-bottom-6">
<summary>How emphasis look rendered as HTML</summary>
Make an *emphatic* statement.

Make an **emphatic** statement.
</details>

### Strikethrough

```
~~Scratch that.~~
```
{: .padding-2 .bg-base-lightest .overflow-auto}

<details markdown="1" class="margin-top-2 margin-bottom-6">
<summary>How strikethroughs look rendered as HTML</summary>
~~Scratch that.~~
</details>