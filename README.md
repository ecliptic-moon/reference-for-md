# Introduction
The whole purpose of this repository is to provide a simple .md (Markdown) reference.  
If you feel something needs changing, contributions are always accepted.

## Table of Contents
[Headings](https://github.com/ecliptic-moon/reference-for-md#headings-sub-headings-and-sub-sub-headings)  
[Text Formatting](https://github.com/ecliptic-moon/reference-for-md#text-formatting)  
[Text Formatting Pt. 2](https://github.com/ecliptic-moon/reference-for-md#text-formatting-2)  
[Using Monospace](https://github.com/ecliptic-moon/reference-for-md#using-monospace-and-putting-code-examples-into-your-extended-descriptions)  
[Lists](https://github.com/ecliptic-moon/reference-for-md#lists)

&nbsp;

## Headings, sub-headings and sub-sub-headings
The `#` symbol creates a larger heading to work with, this could be used for a title.  
On the other hand, `##` creates a smaller version of the heading, and `###` creates a smaller version of the sub-heading.<br/>

&nbsp;

Examples of all 3:
# Heading
## Sub-heading  
### Sub-sub-heading

&nbsp;

## Text formatting
Text can be formatted into a URL (uniform resource locator); turned into bold and italic text; the possibilities are endless!  
Specifically, I'll cover how to do bold and italic text this time around.

Bold text is done like so; `**Text**`  
Italics, on the other hand, are done like this; `_Text_`

&nbsp;

Examples of both:  
**Bold!**  
_Italic!_

&nbsp;

## Text formatting (2)
In this instance of text formatting, I'll cover how to turn text into a URL (The meaning of URL has been stated above).

To do this, you follow this simple syntax; `[Text](https://link)`

&nbsp;

Example:  
[GitHub!](https://github.com)

&nbsp;

## Using monospace and putting code examples into your extended descriptions
To do this, simply wrap backticks (\`) around the text you want to codify.  
Example: \`test\` -> `test`.

In order to create a bigger codeblock for larger code examples, do the following:  
\`\`\`  
TEXT  
\`\`\`  
Notice the triple backticks? 3 backticks on the top and bottom indicate that you're creating a larger codeblock.

The above example should output the following:
```
TEXT
```

&nbsp;

## Lists
There are 2 types of lists included in markdown.

They are:  
1] Ordered lists  
2] Unordered lists

&nbsp;

Unordered list:  
* Like this
* Add another list item
* Another?

It's done like so:  
`* List item`

&nbsp;

Ordered list:  
1. Like this  
2. Add another  
3. Andddd, another

It's done like so:  
`1. List item`  
`2. List item 2`  
`3. List item 3`
