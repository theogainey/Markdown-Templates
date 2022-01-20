# GitHub Flavored Markdown Cheat Sheet
The fist step to mastering the art of `readme.md` is mastering GitHub Flavored Markdown

## Headers 
```
# H1
## H2
### H3
#### H4
##### H5
###### H6

```
# H1
## H2
### H3
#### H4
##### H5
###### H6

## Emphasis
```
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~
```

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

## Lists 
```
1. A numbered list
2. Is numbered
3. With periods and a space

* An Unordered list can use asterisks
- Or minuses
+ Or pluses

```
1. A numbered list
2. Is numbered
3. With periods and a space

* Unordered list can use asterisks
- Or minuses
+ Or pluses

## Links

```
[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/main/README.md)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com
```
[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/main/README.md)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

## Images
```
Inline-style: 
![alt text](https://github.com/theogainey/Markdown-Templates/blob/main/GitHub-Mark-64px.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/theogainey/Markdown-Templates/blob/main/GitHub-Mark-64px.png "Logo Title Text 2"
```

Inline-style: 
![alt text](https://github.com/theogainey/Markdown-Templates/blob/main/GitHub-Mark-64px.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/theogainey/Markdown-Templates/blob/main/GitHub-Mark-64px.png "Logo Title Text 2"

## Code Blocks
```
Inline `code` has `back-ticks around` it.
```
Inline `code` has `back-ticks around` it.

Blocks of code are either fenced by lines with three back-ticks ```
Blocks of code also support Syntax Highlighting.

```
``javascript
const s = "JavaScript syntax highlighting";
alert(s);
``
 
``python
s = "Python syntax highlighting"
print s
``
 
``
No language indicated, so no syntax highlighting. 
`` 
```

```javascript
const s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```
 
```
No language indicated, so no syntax highlighting. 
```

## Tables
Tables aren't part of the core Markdown spec, but they are supported in GitHub Flavored Markdown.

```
Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
```

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

## Blockquotes
```
> Blockquotes are very handy to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote. 
```
> Blockquotes are very handy to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.

## Horizontal Rule 
```
Three or more...

---

Hyphens

***

Asterisks

___

Underscores
```
Three or more...

---

Hyphens

***

Asterisks

___

Underscores


