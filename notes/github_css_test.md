
# h1 Heading
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading


## Horizontal Rules

___

---

***


## Typographic replacements

Enable typographer option to see result.

(c) (C) (r) (R) (tm) (TM) (p) (P) +-

test.. test... test..... test?..... test!....

!!!!!! ???? ,,  -- ---

"Smartypants, double quotes" and 'single quotes'


## Emphasis

**This is bold text**

__This is bold text__

*This is italic text*

_This is italic text_

~~Strikethrough~~


## Blockquotes


> Blockquotes can also be nested...
>> ...by using additional greater-than signs right next to each other...
> > > ...or with spaces between arrows.

## Callouts / Alerts

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

## Lists

Unordered

+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    * Ac tristique libero volutpat at
    + Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
+ Very easy!

Ordered

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa


1. You can use sequential numbers...
1. ...or keep all the numbers as `1.`

Start numbering with offset:

57. foo
1. bar


## Code

Inline `code`

Indented code

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code


Block code "fences"

```
Sample text here...
```

Syntax highlighting

``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

## Tables

| Option | Description                                                               |
| ------ | ------------------------------------------------------------------------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default.    |
| ext    | extension to be used for dest files.                                      |

Right aligned columns

| Option |                                                               Description |
| -----: | ------------------------------------------------------------------------: |
|   data | path to data files to supply the data that will be passed into templates. |
| engine |    engine to be used for processing templates. Handlebars is the default. |
|    ext |                                      extension to be used for dest files. |


## Links

[link text](http://dev.nodeca.com)

[link with title](http://nodeca.github.io/pica/demo/ "title text!")

Autoconverted link https://github.com/nodeca/pica (enable linkify to see)

<a href=".">HTML Links</a>

#### An H4 Markdown Header [Link](blah.html)

## Images

![Minion](https://octodex.github.com/images/minion.png)
![Stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat")

Like links, Images also have a footnote style syntax

![Alt text][id]

With a reference later in the document defining the URL location:

[id]: https://octodex.github.com/images/dojocat.jpg  "The Dojocat"


## Plugins

The killer feature of `markdown-it` is very effective support of
[syntax plugins](https://www.npmjs.org/browse/keyword/markdown-it-plugin).


### [Emojies](https://github.com/markdown-it/markdown-it-emoji)

> Classic markup: :wink: :crush: :cry: :tear: :laughing: :yum:
>
> Shortcuts (emoticons): :-) :-( 8-) ;)

see [how to change output](https://github.com/markdown-it/markdown-it-emoji#change-output) with twemoji.


### [Subscript](https://github.com/markdown-it/markdown-it-sub) / [Superscript](https://github.com/markdown-it/markdown-it-sup)

- 19^th^
- H~2~O


### [\<ins>](https://github.com/markdown-it/markdown-it-ins)

++Inserted text++


### [\<mark>](https://github.com/markdown-it/markdown-it-mark)

==Marked text==


### [Footnotes](https://github.com/markdown-it/markdown-it-footnote)

Footnote 1 link[^first].

Footnote 2 link[^2].

Inline footnote^[Text of inline footnote] definition.

Duplicated footnote reference[^second].

[^first]: Footnote **can have markup**

    and multiple paragraphs.

[^2]: Footnote text.


### [Definition lists](https://github.com/markdown-it/markdown-it-deflist)

Term 1

:   Definition 1
with lazy continuation.

Term 2 with *inline markup*

:   Definition 2

        { some code, part of Definition 2 }

    Third paragraph of definition 2.

_Compact style:_

Term 1
  ~ Definition 1

Term 2
  ~ Definition 2a
  ~ Definition 2b


### [Abbreviations](https://github.com/markdown-it/markdown-it-abbr)

This is HTML abbreviation example.

It converts "HTML", but keep intact partial entries like "xxxHTMLyyy" and so on.

*[HTML]: Hyper Text Markup Language

### [Custom containers](https://github.com/markdown-it/markdown-it-container)

::: warning
*here be dragons*
:::

<div>
<h1>HTML Form Elements Reference</h1>

<h2>Text Inputs</h2>
<label for="text">Text Input:</label>
<input type="text" id="text" name="text" placeholder="Enter text">
<br><br>

<label for="password">Password:</label>
<input type="password" id="password" name="password">
<br><br>

<label for="email">Email:</label>
<input type="email" id="email" name="email">
<br><br>

<label for="tel">Telephone:</label>
<input type="tel" id="tel" name="tel">
<br><br>

<label for="url">URL:</label>
<input type="url" id="url" name="url">
<br><br>

<label for="search">Search:</label>
<input type="search" id="search" name="search">

<pre><code>&lt;label for="text"&gt;Text Input:&lt;/label&gt;
&lt;input type="text" id="text" name="text" placeholder="Enter text"&gt;

&lt;label for="password"&gt;Password:&lt;/label&gt;
&lt;input type="password" id="password" name="password"&gt;

&lt;label for="email"&gt;Email:&lt;/label&gt;
&lt;input type="email" id="email" name="email"&gt;

&lt;label for="tel"&gt;Telephone:&lt;/label&gt;
&lt;input type="tel" id="tel" name="tel"&gt;

&lt;label for="url"&gt;URL:&lt;/label&gt;
&lt;input type="url" id="url" name="url"&gt;

&lt;label for="search"&gt;Search:&lt;/label&gt;
&lt;input type="search" id="search" name="search"&gt;</code></pre>

<hr>

<h2>Number and Date Inputs</h2>
<label for="number">Number:</label>
<input type="number" id="number" name="number" min="0" max="100">
<br><br>

<label for="range">Range:</label>
<input type="range" id="range" name="range" min="0" max="100">
<br><br>

<label for="date">Date:</label>
<input type="date" id="date" name="date">
<br><br>

<label for="time">Time:</label>
<input type="time" id="time" name="time">
<br><br>

<label for="datetime">Datetime-local:</label>
<input type="datetime-local" id="datetime" name="datetime">
<br><br>

<label for="month">Month:</label>
<input type="month" id="month" name="month">
<br><br>

<label for="week">Week:</label>
<input type="week" id="week" name="week">

<pre><code>&lt;label for="number"&gt;Number:&lt;/label&gt;
&lt;input type="number" id="number" name="number" min="0" max="100"&gt;

&lt;label for="range"&gt;Range:&lt;/label&gt;
&lt;input type="range" id="range" name="range" min="0" max="100"&gt;

&lt;label for="date"&gt;Date:&lt;/label&gt;
&lt;input type="date" id="date" name="date"&gt;

&lt;label for="time"&gt;Time:&lt;/label&gt;
&lt;input type="time" id="time" name="time"&gt;

&lt;label for="datetime"&gt;Datetime-local:&lt;/label&gt;
&lt;input type="datetime-local" id="datetime" name="datetime"&gt;

&lt;label for="month"&gt;Month:&lt;/label&gt;
&lt;input type="month" id="month" name="month"&gt;

&lt;label for="week"&gt;Week:&lt;/label&gt;
&lt;input type="week" id="week" name="week"&gt;</code></pre>

<hr>

<h2>Selection Inputs</h2>
<label for="color">Color:</label>
<input type="color" id="color" name="color">
<br><br>

<label for="file">File:</label>
<input type="file" id="file" name="file">

<pre><code>&lt;label for="color"&gt;Color:&lt;/label&gt;
&lt;input type="color" id="color" name="color"&gt;

&lt;label for="file"&gt;File:&lt;/label&gt;
&lt;input type="file" id="file" name="file"&gt;</code></pre>

<hr>

<h2>Checkboxes</h2>
<input type="checkbox" id="check1" name="check1">
<label for="check1">Checkbox 1</label>
<br>
<input type="checkbox" id="check2" name="check2" checked>
<label for="check2">Checkbox 2 (checked)</label>

<pre><code>&lt;input type="checkbox" id="check1" name="check1"&gt;
&lt;label for="check1"&gt;Checkbox 1&lt;/label&gt;

&lt;input type="checkbox" id="check2" name="check2" checked&gt;
&lt;label for="check2"&gt;Checkbox 2 (checked)&lt;/label&gt;</code></pre>

<hr>

<h2>Radio Buttons</h2>
<input type="radio" id="radio1" name="radio-group" value="option1">
<label for="radio1">Radio Option 1</label>
<br>
<input type="radio" id="radio2" name="radio-group" value="option2">
<label for="radio2">Radio Option 2</label>
<br>
<input type="radio" id="radio3" name="radio-group" value="option3" checked>
<label for="radio3">Radio Option 3 (checked)</label>

<pre><code>&lt;input type="radio" id="radio1" name="radio-group" value="option1"&gt;
&lt;label for="radio1"&gt;Radio Option 1&lt;/label&gt;

&lt;input type="radio" id="radio2" name="radio-group" value="option2"&gt;
&lt;label for="radio2"&gt;Radio Option 2&lt;/label&gt;

&lt;input type="radio" id="radio3" name="radio-group" value="option3" checked&gt;
&lt;label for="radio3"&gt;Radio Option 3 (checked)&lt;/label&gt;</code></pre>

<hr>

<h2>Textarea</h2>
<label for="textarea">Textarea:</label>
<br>
<textarea id="textarea" name="textarea" rows="4" cols="50" placeholder="Enter multiple lines of text"></textarea>

<pre><code>&lt;label for="textarea"&gt;Textarea:&lt;/label&gt;
&lt;textarea id="textarea" name="textarea" rows="4" cols="50" placeholder="Enter multiple lines of text"&gt;&lt;/textarea&gt;</code></pre>

<hr>

<h2>Select Dropdown</h2>
<label for="select">Select:</label>
<select id="select" name="select">
    <option value="">--Please choose an option--</option>
    <option value="option1">Option 1</option>
    <option value="option2">Option 2</option>
    <option value="option3">Option 3</option>
</select>
<br><br>

<label for="select-multiple">Multiple Select:</label>
<select id="select-multiple" name="select-multiple" multiple size="4">
    <option value="opt1">Multiple Option 1</option>
    <option value="opt2">Multiple Option 2</option>
    <option value="opt3">Multiple Option 3</option>
    <option value="opt4">Multiple Option 4</option>
</select>

<pre><code>&lt;label for="select"&gt;Select:&lt;/label&gt;
&lt;select id="select" name="select"&gt;
&lt;option value=""&gt;--Please choose an option--&lt;/option&gt;
&lt;option value="option1"&gt;Option 1&lt;/option&gt;
&lt;option value="option2"&gt;Option 2&lt;/option&gt;
&lt;option value="option3"&gt;Option 3&lt;/option&gt;
&lt;/select&gt;

&lt;label for="select-multiple"&gt;Multiple Select:&lt;/label&gt;
&lt;select id="select-multiple" name="select-multiple" multiple size="4"&gt;
&lt;option value="opt1"&gt;Multiple Option 1&lt;/option&gt;
&lt;option value="opt2"&gt;Multiple Option 2&lt;/option&gt;
&lt;option value="opt3"&gt;Multiple Option 3&lt;/option&gt;
&lt;option value="opt4"&gt;Multiple Option 4&lt;/option&gt;
&lt;/select&gt;</code></pre>

<hr>

<h2>Buttons</h2>
<button type="button">Button (type="button")</button>
<button type="submit">Submit Button</button>
<button type="reset">Reset Button</button>
<br><br>

<input type="button" value="Input Button">
<input type="submit" value="Input Submit">
<input type="reset" value="Input Reset">

<pre><code>&lt;button type="button"&gt;Button (type="button")&lt;/button&gt;
&lt;button type="submit"&gt;Submit Button&lt;/button&gt;
&lt;button type="reset"&gt;Reset Button&lt;/button&gt;

&lt;input type="button" value="Input Button"&gt;
&lt;input type="submit" value="Input Submit"&gt;
&lt;input type="reset" value="Input Reset"&gt;</code></pre>

<hr>

<h2>Other Inputs</h2>
<input type="hidden" name="hidden" value="hidden-value">
<label>(Hidden input - not visible)</label>
<br><br>

<input type="image" src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='30'%3E%3Crect width='100' height='30' fill='lightblue'/%3E%3Ctext x='50' y='20' text-anchor='middle' font-size='14'%3EImage Button%3C/text%3E%3C/svg%3E" alt="Image Button">

<pre><code>&lt;input type="hidden" name="hidden" value="hidden-value"&gt;

&lt;input type="image" src="button-image.png" alt="Image Button"&gt;</code></pre>

<hr>

<h2>Datalist</h2>
<label for="datalist">Input with Datalist:</label>
<input list="browsers" id="datalist" name="datalist">
<datalist id="browsers">
    <option value="Chrome">
    <option value="Firefox">
    <option value="Safari">
    <option value="Edge">
    <option value="Opera">
</datalist>

<pre><code>&lt;label for="datalist"&gt;Input with Datalist:&lt;/label&gt;
&lt;input list="browsers" id="datalist" name="datalist"&gt;
&lt;datalist id="browsers"&gt;
&lt;option value="Chrome"&gt;
&lt;option value="Firefox"&gt;
&lt;option value="Safari"&gt;
&lt;option value="Edge"&gt;
&lt;option value="Opera"&gt;
&lt;/datalist&gt;</code></pre>

<hr>

<h2>Fieldset and Legend</h2>
<fieldset>
    <legend>Grouped Form Elements</legend>
    <label for="field1">Field 1:</label>
    <input type="text" id="field1" name="field1">
    <br><br>
    <label for="field2">Field 2:</label>
    <input type="text" id="field2" name="field2">
</fieldset>

<pre><code>&lt;fieldset&gt;
&lt;legend&gt;Grouped Form Elements&lt;/legend&gt;
&lt;label for="field1"&gt;Field 1:&lt;/label&gt;
&lt;input type="text" id="field1" name="field1"&gt;

&lt;label for="field2"&gt;Field 2:&lt;/label&gt;
&lt;input type="text" id="field2" name="field2"&gt;
&lt;/fieldset&gt;</code></pre>
</div>
