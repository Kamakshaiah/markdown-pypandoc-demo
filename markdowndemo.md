# Table of contents
1. [Title](#Title)
2. [External links](#External links)
3. [Images](#Images)
4. [Quotes](#Quotes)
5. [Lists](#Lists)
	1. [Ordered list](#Ordered list)
	2. [Nested lists](#Nested lists)
	3. [Mixed lists](#Mixed lists)
6. [Line breaks](#Line breaks)
7. [Tables](#Tables)
8. [Math inside RMarkdown](#Math inside RMarkdown)
9. [URLs and Emails](#URLs and Emails)
10. [Code Blocks](#Code Blocks)
	1. [Plain Code](#Plain Code)
11. [Horizontal Rules](#Horizontal Rules)
12. [Formatting Links](#Formatting Links)
13. [HTML code in markdown](#HTML code in markdown)


## This is Title (level 2) <a name="Title"></a>

Titles are created either using `#`. For instace at level 1 it can be `#`, level 2 `##` and so on... `##` make the sub-title just as below.  

	## This is subheading/ heading two (at level 3)	

>## This is subheading/ heading two (at level 3)

**_Lorem Ipsum_** is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, 
when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into 
electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, 
and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

### External links <a name="External links"></a> 
[Visit wikipedia](www.wikipedia.org) This is a link that redirects to Wikipedia. 

### Internal links <a name="Inernal links"></a> 

This statement shows as how to provide a [reference link][1]  and a reference to [external url][2]. 

### images <a name="Images"></a> 

The below url spots to wikipedia logo
![Wikipedia](https://www.wikipedia.org/portal/wikipedia.org/assets/img/Wikipedia-logo-v2.png)

This is reference image link. This links to [wikipedia][wiki] image. 

### Quotes <a name="Quotes"></a> 

The following is a single line quote

> this is a quote

The following multiline _blockquote_. 

>**_Lorem Ipsum_** is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, 
when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into 
electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, 
and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
>
>**_Lorem Ipsum_** is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, 
when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into 
electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, 
and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

**_Lorem Ipsum_** is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, 
when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into 
electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, 
and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

### Lists <a name="Lists"></a> 

'*' is useful to do lists in markdown. The following is a typical list done using _asterisk_ symbol. 

* first line
* second line
* third line

#### Ordered list <a name="Ordered list"></a> 

An ordered list is prefaced with numbers, instead of asterisks. Take a look at this recipe:

1. ordered list line one
2. ordered list line two 
3. ordered list line three

You can choose to add italics, bold, or links within lists, as you might expect. In the box below, turn the latin names for the plants into italics.

1. ordered list **line one**
2. ordered list _line two_ 
3. ordered list **_line three_**

#### Nested lists (or sub-lists) <a name="Nested lists"></a> 

Occasionally, you might find the need to make a list with more depth, or, to nest one list within another. Have no fear, because the Markdown syntax is exactly 
the same. All you have to do is to remember to indent each asterisk one space more than the preceding item.

* this is line one in unordered list 
 * this line one indented by one space makes this line nested under line one. 
* this is line two in unordered list 
 * this line one indented by one space makes this line nested under line two.
 * this line two indented by one space makes this line nested under line two.
* this is line three in unordered list 
 * this line one indented by one space makes this line nested under line three.
 * this line two indented by one space makes this line nested under line three.
 * this line three indented by one space makes this line nested under line three.

#### Mixed lists <a name="Mixed lists"></a> 

There's one more trick to lists and indentation that we'll explore, and that deals with the case of paragraphs. Suppose you want to create a bullet list 
that requires some additional context (but not another list).

1. Crack three eggs over a bowl.

 Now, you're going to want to crack the eggs in such a way that you don't make a mess.

 If you _do_ make a mess, use a towel to clean it up!

2. Pour a gallon of milk into the bowl.

 Basically, take the same guidance as above: don't be messy, but if you are, clean it up!

3. Rub the salmon vigorously with butter.

   By "vigorous," we mean a strictly vertical motion. Julia Child once quipped:
   > Up and down and all around, that's how butter on salmon goes.
4. Drop the salmon into the egg-milk bowl.

   Here are some techniques on salmon-dropping:

   * Make sure no trout or children are present
   * Use both hands
   * Always have a towel nearby in case of messes

### Line breaks <a name="Line breaks"></a> 

Following line will be rendered as sinle line

"Do I contradict myself?
Very well then I contradict myself,
(I am large, I contain multitudes.)"

We need to write as below to make line breaks. 

"Do I contradict myself?

Very well then I contradict myself,

(I am large, I contain multitudes.)"

### Tables <a name="Tables"></a> 

#### **Table 1**: _a sample table_

| col 1 | col 2 | col 3 |
|:------|:-----:|------:|
| val 1 | val 2 | [line](www.wikipedia.org) |
| val 1 | val 2 | **val 3** |
| val 1 | val 2 | _val \|_ |

### Math inside RMarkdown <a name="Math inside RMarkdown"></a> 

#### Symbols 

| Symbol | Script |
|:-------|-------:|
| $\alpha$ | \alpha |
| $A$	| A |
| $\beta$ | \beta |
| $B$| B |
| $\gamma$ | \gammma |
| $\Gamma$ | \Gamma |
| $\pi$ | \pi |
| $\Pi$ | \Pi |
| $\phi$ | \phi |
| $\Phi$ | \Phi |
| $\varphi$ | \varphi |
| $\theta$ | \theta |

#### Power and Indices

| Symbol | Script |
|:-------|-------:|
| $\frac{n!}{k!(n-k)!}$	| \frac{n!}{k!(n-k)!} |
| $\binom{n}{k}$ | \binom{n}{k} |
| $\frac{\frac{x}{1}}{x - y}$ | \frac{\frac{x}{1}}{x - y} |
| $^3/_7$ | ^3/_7 | 

#### Roots

| Symbol | Script |
|:-------|-------:| 
| $\sqrt{k}$ | \sqrt{k} |
| $\sqrt[n]{k}$ | \sqrt[n]{k} |

Refer [to this link](https://csrgxtu.github.io/2015/03/20/Writing-Mathematic-Fomulars-in-Markdown/) for rest of the material. 

### URLs and Email Addresses <a name="URLs and Emails"></a> 

Angle brackets are used for URL. For instancd: go to <https://pypi.org/project/pypandoc/> pypandoc documentation. 
`` `<fake@example.com>` `` creates an email just like <fake@example.com>. 

### Code Blocks <a name="Code Blocks"></a> 

To create code blocks, indent every line of the block by at least four spaces or one tab.

    <html>
      <head>
      </head>
    </html>

In the above code the fist line is indented by _4 spaces_ or _one tab_.
Code blocks are normally indented four spaces or one tab. When they’re in a list, indent them eight spaces or two tabs.

1. Open the file.
2. Find the following code block on line 21:

        <html>
            <head>
            <title>Test</title>  
        </head>

3. Update the title to match the name of your website.

#### Plain Code <a name="Plain Code"></a> 

To denote a word or phrase as code, enclose it in backticks (`). For instance: 

At the command prompt, type `nano`.

#### Escaping Backticks

If the word or phrase you want to denote as code includes one or more backticks, you can escape it by enclosing the word or phrase in double backticks (``).

``Use `code` in your Markdown file.``

### Horizontal Rules <a name="Horizontal Rules"></a>

To create a horizontal rule, use three or more asterisks (***), dashes (---), or underscores (___) on a line by themselves.

Try to put a blank line before...

---

...and after a horizontal rule.

### Formatting Links <a name="Formatting Links"></a>

To emphasize links, add asterisks before and after the brackets and parentheses. To denote links as code, add backticks in the brackets.


	I love supporting the **[EFF](https://eff.org)**.
	This is the *[Markdown Guide](https://www.markdownguide.org)*.
	See the section on [`code`](#code).

The rendered output looks like this:

I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).

### HTML code in markdown <a name="HTML code in markdown"></a>

Many Markdown applications allow you to use HTML tags in Markdown-formatted text. This is helpful if you prefer certain HTML tags to Markdown syntax. 
For example, some people find it easier to use HTML tags for images. Using HTML is also helpful when you need to change the attributes of an element, 
like specifying the color of text or changing the width of an image.

To use HTML, place the tags in the text of your Markdown-formatted file.

	This **word** is bold. This <em>word</em> is italic.
	The rendered output looks like this:

This **word** is bold. This word is <em>italic<em>.

### References
[1]: this links/cites to 1 in the text
[2]: www.wikipedia.org
[wiki]: https://www.wikipedia.org/portal/wikipedia.org/assets/img/Wikipedia-logo-v2.png 
Refere to <https://www.markdownguide.org/basic-syntax/> for more inforamtion
