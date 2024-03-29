# Learning playwright using javascript
[Document](https://playwright.dev/docs/intro)
### Applications Supported
- Web browser apps
- Mobile web apps
- API's

### Languages Supported
- Javascript
- Typescript
- Java
- Python
- .Net(C#)

### Browser Supported (headed/headless)
- Chromium
- Webkit (Safari)
- Firefox

### OS supported
- Windows
- Linux
- MacOS
- Support CI runs

## Main Features
1. Free and open source
2. Support multi-browser, multi-langiage, multi-OS
3. Easy setup and configuration
4. Functional, API, accessibility testsing (using third party plugins)
5. Builtin reporters, custom reports
6. CI/CD, Docker
7. Parallel Testing (No dependency on TestNG)
8. Auto wait - resilient - less flaky tests
9. Built-in assertions
10. Multi tab and multi window support
11. Iframe, shadow DOM's
12. Test parameter
13. Emulate mobile devices
14. Fast Execution
15. Powerful tooling - codegen, playwright inspector, trace viewer
# ----------Markdown Cheatsheet-----------------------------
Markdown Headers
There are two ways to create a header in Markdown: by using hashes or by using underlines.

Hashes
The first option, creating headers with hash signs, is more compact and quicker to type:

# Primary header (similar to HTML H1 tag)
## Secondary header (similar to HTML H2 tag)
### Tertiary header (similar to HTML H3 tag)
#### Quaternary header (similar to HTML H4 tag)
Underlined headers
Alternatively, you can ‘underline’ your header. It’s a bit more work, but some people prefer it since it stands out more when looking at the plain text. Note that you can only use this for primary and secondary headers:

Primary header (similar to a HTML H1 tag)
=========================================
Secondary header (similar to a HTML H2 tag)
-------------------------------------------
Emphasis (bold, italic)
There are three ways to emphasize a piece of text that we’ll show in this markdown sheet cheat:

By making it bolder than the surrounding text
Using italics
Or combining bold and italics
Make bold text with markdown (strong emphasis)
To create bold text, also called strong emphasis, surround it with two asterisks or two underscores. What you use is a matter of taste.

This is how you create **bold** text
When converted to HTML or PDF, it will result in: “This is how you create bold text”.

This is the same, but with underscores:

This is how you create __bold__ text
Italics with markdown (emphasis)
To create italic text, also called emphasis, support the text with single asterisks or underscores. Again, it’s a matter of taste which one you choose:

This is how you create *italic* text
When converted to HTML or PDF, it will result in:: “This is how you create italic text.”

The same, but with underscores:

This is how you create _italic_ text
Combine bold and italics
You can combine both, resulting in bold italics text. You can either mix and match or use triple underscores or triple asterisks like this:

This is how you create **_bold italics_** text.
This is how you create ___bold italics___ text.
This is how you create ***bold italics*** text.
The result when converted to HTML or PDF:

This is how you create bold italics text.
Strikethrough
You can strikethrough your text as follows:

This is how you create ~~strikethrough~~ text.
This results in: “This is how you create strikethrough text.”

Markdown Lists
You can either create ordered (numbered) lists or unordered lists. Both types of markdown lists look very natural in plain text, as you’ll see in the examples in this markdown sheet cheat.

Ordered lists
To create an ordered list, create a text list with numbers, one per line:

1. Apples
2. Bananas
3. Peanut butter
I numbered the individual items properly, but you don’t have to. In fact, any number will do. However, properly numbering the items will look better in plain text, but it can be a pain sometimes. For example, if you need to add items in the middle of a long list, you need to renumber all of them.

In the end, use whatever suits you best. I tend to number my lists properly since most lists are small anyway, and it’s easier on the eyes when looking at the source text.

All markdown converters I know of will convert the following into exactly the same list as the one above:

1. Apples
1. Bananas
1. Peanut butter
The result:

1. Apples
2. Bananas
3. Peanut butter
Unordered lists
Unordered lists can be made in two ways:

with asterisks
or by using dashes
The following lists give an identical output when converted into another document format like HTML or PDF:

- Apples
- Bananas
- Peanut butter
and:

* Apples
* Bananas
* Peanut butter
Both result in:

Apples
Bananas
Peanut butter
Checklists (or Task Lists, TODO lists)
Some but not all markdown parsers support checklists. E.g. this works on GitHub and with several markdown plugins for VS Code, for example, but it won’t work within the WordPress Gutenberg editor:

- [x] Apples
- [ ] Bananas
- [ ] Peanut butter
You can use these to keep track of work (TODO list) or tasks that need to be completed.

Links in Markdown
You can use Markdown to link to a website or local file. In fact, most markdown converters will automatically convert a URL to a link, but you better not rely on it. In case of doubt, it’s best to try and see what happens in your specific case.

A basic link
This is an inline-style link to our [markdown cheat sheet](/markdown-cheat-sheet)
You can also create a relative link: [code repo](../repo/code)
Or an absolute, inline-style link to [Google](https://google.com)
URLs like <https://google.com>, and sometimes https://google.com
or even google.com, get converted to clickable links.
Inline-style link with a title attribute to [Markdown Land](https://markdown.land "Markdown Land")
This is an inline-style link to our markdown cheat sheet
You can also create a relative link: code repo
Or an absolute, inline-style link to Google
URLs like https://google.com, and sometimes https://google.com or even google.com, get converted to clickable links.
Inline-style link with a title attribute to Markdown Land
Reference style links
In addition to regular links, markdown also supports reference-style links. We can define these links somewhere in a file, usually at the bottom, and reference them in the text anywhere.

[This website about Markdown][Case-insensitive reference link to Markdown.land]
[The Python.land tutorial with a numbered link][1]
Or leave it empty and use the link text itself, like this: [Python Land].
Text and other Markdown markup, to demonstrate that the reference links can be put anywhere.
Usually, they are placed at the bottom of a document. Because they are reference links, they
won't show up by themselves. So you won't see the links below.
[Case-insensitive reference link to Markdown.land]: https://www.markdown.land
[1]: https://python.land/python-tutorial
[Python Land]: http://python.land
This website about Markdown
The Python.land tutorial with a numbered link
Or leave it empty and use the link text itself, like this: Python Land.

Text and other Markdown markup, to demonstrate that the reference links can be put anywhere.

Usually, they are placed at the bottom of a document. Because they are reference links, they
won’t show up by themselves. So you won’t see the links below.
Tables
I created a separate page explaining all the details about Markdown tables, but for quick reference, here’s an example of a Markdown table with the alignment of the price and availability columns:

| Item         | Price | # In stock |
|--------------|:-----:|-----------:|
| Juicy Apples |  1.99 |        739 |
| Bananas      |  1.89 |          6 |
Head over to the Markdown table page for all the details, including column alignment and links to handy table generators to save you time and effort.

Emoji’s
Let me start with the disclaimer: use emojis sparingly to not annoy your readers or look like a child 😅

There are two ways to add emojis to your Markdown file:

by copying the Unicode character and pasting it in your file
By using an emoji shortcode
Copy and pasting emojis into Markdown
A quick and easy method is to copy and paste the emoji. Many sites help you find and copy emojis. Here’s one, and here’s another one. Select the emoji you like, hit control + c, and paste it in your markdown file with control + v. If you’re on a mac, that would be cmd+c and cmd+v.

Using shortcodes
I don’t recommend this method since it’s less readable. But in rare cases, you might prefer it. E.g., if your text document is not stored in Unicode format. Not all parses will support this method, but you can always try.

An emoji shortcode is a word surrounded by colons like these:

🙂
:laughing:
😉
… etcetera