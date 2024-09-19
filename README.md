# Introduction to Styles in CSS

Web developers came to understand the limitations of standard HTML tags and wanted to improve on what they could do.  They created an attribute for html tags called a style.  This allowed developers to add a lot more customized functionality to their tags, often being able to replace several tags with a single tag.  In fact, in many modern browsers, the classic html tags are no longer used at all.

The div and span tags have taken over as the tags that are used most frequently these days.  In fact, if you look at the *Elements* in your browser's *Developer Tools*, you will see almost exclusively div, span, script and style tags for most modern browsers, and that's because we can customize those styles.

Open up the page1.html file and preview what it looks like.  You will notice the difference between the div and span tags, and see why they are both used.

```
What is the main difference between a div and a span tag?
```

 # Inline vs Blocks
 <span> is considered an *inline* tag, which means that it preserves the line spacing.  This means that if the tag appears  in the middle of the line, then the container tag contents will still be in the middle of the line.  A <div> tag is a block tag, which means that the content will be pulled out of the line, almost as though it was a paragraph.  Later on, we will see that we can actually make blocks into *inline blocks*, which means that the blocks can appear side by side, rather than vertically, like paragraphs.

# Inline Styles
Styles are a huge part of modern webpage development.  A style can be applied in many ways, but we will look at the simplest way first.
A style can be added to any html tag with an attribute:
```
<div style="color: red; text-decoration: underline;" >This is red and underlined</div>
```
Copy this tag to your page1.html file and add it to the body.  Preview the document.  Notice how it looks?  You can include many styles within a single container tag. They have 2 parts: the style and the value are separated by a colon.  If you want to add multiple styles, you separate them with a semi-colon.

There are thousands of different combinations possible with styles and different values, and they can go beyond basic formatting, but include creation of layouts and special effects.  Styles are now responsible for most of the animations on webpages as well.

# Color in styles
We can use a number of colors that come from keywords in the styles list.  Basic color names are generally acceptable, but we can also use the RGB color scheme. Read more about rgb colors at:
https://www.w3schools.com/cssref/func_rgb.asp
and about hexadecimal colors at:
https://www.w3schools.com/css/css_colors_hex.asp

# Assignment
Today we will be researching some of the possibilities that can be accomplished with styles.  You will include them in a document so that you can refer to them later. 
1. Do a Google search for different styles.
2. Identify the most interesting styles that you think you might use
3. For each style, create a tag and an example in the "styles.html" document.
