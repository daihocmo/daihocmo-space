

## Heading

"To create a heading, add number signs (`#`) in front of a word or phrase. The number of number signs you use should correspond to the heading level. For example, to create a heading level three (`<h3>`), use three number signs (e.g., `### My Header`)."

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
     
      <th>Rendered Output</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code class="highlighter-rouge"># Heading level 1</code></td>
      <td><code class="highlighter-rouge">&lt;h1&gt;Heading level 1&lt;/h1&gt;</code></td>
      <td><h1 class="no-anchor" data-toc-skip>Heading level 1</h1></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">## Heading level 2</code></td>
      <td><code class="highlighter-rouge">&lt;h2&gt;Heading level 2&lt;/h2&gt;</code></td>
      <td><h2 class="no-anchor" data-toc-skip>Heading level 2</h2></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">### Heading level 3</code></td>
      <td><code class="highlighter-rouge">&lt;h3&gt;Heading level 3&lt;/h3&gt;</code></td>
      <td><h3 class="no-anchor" data-toc-skip>Heading level 3</h3></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">#### Heading level 4</code></td>
      <td><code class="highlighter-rouge">&lt;h4&gt;Heading level  4&lt;/h4&gt;</code></td>
      <td><h4 class="no-anchor">Heading level 4</h4></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">##### Heading level 5</code></td>
      <td><code class="highlighter-rouge">&lt;h5&gt;Heading level 5&lt;/h5&gt;</code></td>
      <td><h5 class="no-anchor">Heading level 5</h5></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">###### Heading level 6</code></td>
      <td><code class="highlighter-rouge">&lt;h6&gt;Heading level 6&lt;/h6&gt;</code></td>
      <td><h6 class="no-anchor">Heading level 6</h6></td>
    </tr>
  </tbody>
</table>

### Heading Best Practices

Markdown applications don't agree on how to handle a missing space between the number signs (`#`) and the heading name. For compatibility, always put a space between the number signs and the heading name.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Do this</th>
      <th>❌&nbsp; Don't do this</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
          # Here's a Heading<br><br>
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          #Here's a Heading
        </code>
      </td>
    </tr>
  </tbody>
</table>

You should also put blank lines before and after a heading for compatibility.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Do this</th>
      <th>❌&nbsp; Don't do this</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
        Try to put a blank line before...<br><br>

        # Heading<br><br>

        ...and after a heading.
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
        Without blank lines, this might not look right.<br>
        # Heading<br>
        Don't do this!
        </code>
      </td>
    </tr>
  </tbody>
</table>




### Paragraph

To create paragraphs, use a blank line to separate one or more lines of text.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
      <th>Rendered Output</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
          I really like using Markdown.<br /><br />

          I think I'll use it to format all of my documents from now on.
        </code>
      </td>
      <td>
        <p>I really like using Markdown.</p>

        <p>I think I'll use it to format all of my documents from now on.</p>
      </td>
    </tr>
  </tbody>
</table>

### Paragraph Best Practices

Unless the [paragraph is in a list](/basic-syntax/#paragraphs), don't indent paragraphs with spaces or tabs.

<div class="alert alert-info">
  <i class="fas fa-info-circle"></i> <strong>Note:</strong> If you need to indent paragraphs in the output, see the section on how to <a href="/hacks/#indent-tab">indent (tab)</a>.
</div>

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Do this</th>
      <th>❌&nbsp; Don't do this</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
          Don't put tabs or spaces in front of your paragraphs.<br><br>

          Keep lines left-aligned like this.<br><br>
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
        &nbsp;&nbsp;&nbsp;&nbsp;This can result in unexpected
        formatting problems.<br><br>

        &nbsp;&nbsp;Don't add tabs or spaces in front of paragraphs.
        </code>
      </td>
    </tr>
  </tbody>
</table>


## Linebreak

To create a line break or new line (`<br>`), end a line with two or more spaces, and then type return.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
      <th>Rendered Output</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
          This is the first line. &nbsp;<br />
          And this is the second line.
        </code>
      </td>
      <td>
        <p>This is the first line.<br />   
        And this is the second line.</p>
      </td>
    </tr>
  </tbody>
</table>

### Line Break Best Practices

You can use two or more spaces (commonly referred to as "trailing whitespace") for line breaks in nearly every Markdown application, but it's controversial. It's hard to see trailing whitespace in an editor, and many people accidentally or intentionally put two spaces after every sentence. For this reason, you may want to use something other than trailing whitespace for line breaks. If your Markdown application [supports HTML](/basic-syntax/#html), you can use the `<br>` HTML tag.

For compatibility, use trailing white space or the `<br>` HTML tag at the end of the line.

There are two other options I don't recommend using. CommonMark and a few other lightweight markup languages let you type a backslash (`\`) at the end of the line, but not all Markdown applications support this, so it isn't a great option from a compatibility perspective. And at least a couple lightweight markup languages don't require anything at the end of the line — just type return and they'll create a line break.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Do this</th>
      <th>❌&nbsp; Don't do this</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
          First line with two spaces after. &nbsp;<br>
          And the next line.<br><br>

          First line with the HTML tag after.&lt;br&gt;<br>
          And the next line.<br><br>
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
        First line with a backslash after.\<br>
        And the next line.<br><br>

        First line with nothing after.<br>
        And the next line.<br><br>
        </code>
      </td>
    </tr>
  </tbody>
</table>


## Emphasis

You can add emphasis by making text bold or italic.

{% include syntax.html type="basic-sub" syntax-id="bold" %}

{% include syntax.html type="basic-sub" syntax-id="italic" %}

### Bold and Italic

To emphasize text with bold and italics at the same time, add three asterisks or underscores before and after a word or phrase. To bold and italicize the middle of a word for emphasis, add three asterisks without spaces around the letters.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
     
      <th>Rendered Output</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code class="highlighter-rouge">This text is ***really important***.</code></td>
      <td>This text is <em><strong>really important</strong></em>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">This text is ___really important___.</code></td>
      <td>This text is <em><strong>really important</strong></em>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">This text is __*really important*__.</code></td>
      <td>This text is <em><strong>really important</strong></em>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">This text is **_really important_**.</code></td>
      <td>This text is <em><strong>really important</strong></em>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">This is really***very***important text.</code></td>
      <td>This is really<em><strong>very</strong></em>important text.</td>
    </tr>
  </tbody>
</table>

<div class="alert alert-info">
  <i class="fas fa-info-circle"></i> <strong>Note:</strong> The order of the <code>em</code> and <code>strong</code> tags might be reversed depending on the Markdown processor you're using.
</div>

#### Bold and Italic Best Practices

Markdown applications don't agree on how to handle underscores in the middle of a word. For compatibility, use asterisks to bold and italicize the middle of a word for emphasis.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Do this</th>
      <th>❌&nbsp; Don't do this</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
          This is really***very***important text.
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          This is really___very___important text.
        </code>
      </td>
    </tr>
  </tbody>
</table>


To create a blockquote, add a `>` in front of a paragraph.

```
> Dorothy followed her through many of the beautiful rooms in her castle.
```

The rendered output looks like this:

> Dorothy followed her through many of the beautiful rooms in her castle.

### Blockquotes with Multiple Paragraphs

Blockquotes can contain multiple paragraphs. Add a `>` on the blank lines between the paragraphs.

```
> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
```

The rendered output looks like this:

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### Nested Blockquotes

Blockquotes can be nested. Add a `>>` in front of the paragraph you want to nest.

```
> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
```

The rendered output looks like this:

> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### Blockquotes with Other Elements

Blockquotes can contain other Markdown formatted elements. Not all elements can be used — you'll need to experiment to see which ones work.

```
> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.
```

The rendered output looks like this:

> <h4 class="no-anchor">The quarterly results look great!</h4>
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
> *Everything* is going according to **plan**.

### Blockquotes Best Practices

For compatibility, put blank lines before and after blockquotes.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Do this</th>
      <th>❌&nbsp; Don't do this</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
        Try to put a blank line before...<br><br>

        > This is a blockquote<br><br>

        ...and after a blockquote.
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
        Without blank lines, this might not look right.<br>
        > This is a blockquote<br>
        Don't do this!
        </code>
      </td>
    </tr>
  </tbody>
</table>


## List 

You can organize items into ordered and unordered lists.

{% include syntax.html type="basic-sub" syntax-id="ordered-lists" %}

{% include syntax.html type="basic-sub" syntax-id="unordered-lists" %}

### Adding Elements in Lists

To add another element in a list while preserving the continuity of the list, indent the element four spaces or one tab, as shown in the following examples.

<div class="alert alert-success">
  <i class="fas fa-lightbulb"></i> <strong>Tip:</strong> If things don't appear the way you expect, double check that you've indented the elements in the list four spaces or one tab.
</div>

#### Paragraphs

```
* This is the first list item.
* Here's the second list item.

    I need to add another paragraph below the second list item.

* And here's the third list item.
```

The rendered output looks like this:

* This is the first list item.
* Here's the second list item.

    I need to add another paragraph below the second list item.

* And here's the third list item.

#### Blockquotes

```
* This is the first list item.
* Here's the second list item.

    > A blockquote would look great below the second list item.

* And here's the third list item.
```

The rendered output looks like this:

* This is the first list item.
* Here's the second list item.

    > A blockquote would look great below the second list item.

* And here's the third list item.

#### Code Blocks {#code-blocks-1}

[Code blocks](#code-blocks) are normally indented four spaces or one tab.  When they're in a list, indent them eight spaces or two tabs.

```text
1. Open the file.
2. Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3. Update the title to match the name of your website.
```

The rendered output looks like this:

1. Open the file.
2. Find the following code block on line 21:

    ```text
    <html>
      <head>
        <title>Test</title>
      </head>
    ```

3. Update the title to match the name of your website.

#### Images

```
1. Open the file containing the Linux mascot.
2. Marvel at its beauty.

    ![Tux, the Linux mascot](/assets/images/tux.png)

3. Close the file.
```

The rendered output looks like this:

1. Open the file containing the Linux mascot.
2. Marvel at its beauty.

    <img srcset="https://mdg.imgix.net/assets/images/tux.png?auto=format&fit=clip&w=100 480w,
             https://mdg.imgix.net/assets/images/tux.png?auto=format&fit=clip&q=40&w=100 1080w"
             src="https://mdg.imgix.net/assets/images/tux.png" class="img-fluid" alt="Tux, the Linux mascot" loading="lazy" sizes="100vw">

3. Close the file.

#### Lists

You can nest an unordered list in an ordered list, or vice versa.

```
1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item
```

The rendered output looks like this:

1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item


## Code

To denote a word or phrase as code, enclose it in backticks (`` ` ``).

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
      <th>Rendered Output</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code class="highlighter-rouge">At the command prompt, type `nano`.</code></td>
      <td>At the command prompt, type <code class="highlighter-rouge">nano</code>.</td>
    </tr>
  </tbody>
</table>

### Escaping Backticks

If the word or phrase you want to denote as code includes one or more backticks, you can escape it by enclosing the word or phrase in double backticks (<code>``</code>).

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
     
      <th>Rendered Output</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>``Use `code` in your Markdown file.``</code></td>
      <td><code>Use `code` in your Markdown file.</code></td>
    </tr>
  </tbody>
</table>

### Code Blocks

To create code blocks, indent every line of the block by at least four spaces or one tab.

```text
    <html>
      <head>
      </head>
    </html>
```

The rendered output looks like this:

```text
<html>
  <head>
  </head>
</html>
```

<div class="alert alert-info">
  <i class="fas fa-info-circle"></i> <strong>Note:</strong> To create code blocks without indenting lines, use <a href="/extended-syntax/#fenced-code-blocks">fenced code blocks</a>.
</div>



To create a horizontal rule, use three or more asterisks (`***`), dashes (`---`), or underscores (`___`) on a line by themselves.

```
***

---

_________________
```

The rendered output of all three looks identical:

---

### Horizontal Rule Best Practices

For compatibility, put blank lines before and after horizontal rules.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Do this</th>
      <th>❌&nbsp; Don't do this</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
        Try to put a blank line before...<br><br>

        ---<br><br>

        ...and after a horizontal rule.
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
        Without blank lines, this would be a heading.<br>
        ---<br>
        Don't do this!
        </code>
      </td>
    </tr>
  </tbody>
</table>

## Link 
To create a link, enclose the link text in brackets (e.g., `[Duck Duck Go]`) and then follow it immediately with the URL in parentheses (e.g., `(https://duckduckgo.com)`).

```
My favorite search engine is [Duck Duck Go](https://duckduckgo.com).
```

The rendered output looks like this:

My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

<div class="alert alert-info">
  <i class="fas fa-info-circle"></i> <strong>Note:</strong> To link to an element on the same page, see <a href="/extended-syntax/#linking-to-heading-ids">linking to heading IDs</a>. To create a link that opens in a new tab or window, see the section on <a href="/hacks/#link-targets">link targets</a>.
</div>

### Adding Titles

You can optionally add a title for a link. This will appear as a tooltip when the user hovers over the link. To add a title, enclose it in quotation marks after the URL.

```
My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").
```

The rendered output looks like this:

My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

### URLs and Email Addresses

To quickly turn a URL or email address into a link, enclose it in angle brackets.

```
<https://www.markdownguide.org>
<fake@example.com>
```

The rendered output looks like this:

<https://www.markdownguide.org><br/>
<fake@example.com>

### Formatting Links

To [emphasize](#emphasis) links, add asterisks before and after the brackets and parentheses. To denote links as [code](#code), add backticks in the brackets.

```
I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).
```

The rendered output looks like this:

I love supporting the **[EFF](https://eff.org)**.<br/>
This is the *[Markdown Guide](https://www.markdownguide.org)*.<br/>
See the section on [`code`](#code).

### Reference-style Links

Reference-style links are a special kind of link that make URLs easier to display and read in Markdown. Reference-style links are constructed in two parts: the part you keep inline with your text and the part you store somewhere else in the file to keep the text easy to read.

#### Formatting the First Part of the Link

The first part of a reference-style link is formatted with two sets of brackets. The first set of brackets surrounds the text that should appear linked. The second set of brackets displays a label used to point to the link you're storing elsewhere in your document.

Although not required, you can include a space between the first and second set of brackets. The label in the second set of brackets is not case sensitive and can include letters, numbers, spaces, or punctuation.

This means the following example formats are roughly equivalent for the first part of the link:

- `[hobbit-hole][1]`
- `[hobbit-hole] [1]`

#### Formatting the Second Part of the Link

The second part of a reference-style link is formatted with the following attributes:

1. The label, in brackets, followed immediately by a colon and at least one space (e.g., `[label]: `).
2. The URL for the link, which you can optionally enclose in angle brackets.
3. The optional title for the link, which you can enclose in double quotes, single quotes, or parentheses.

This means the following example formats are all roughly equivalent for the second part of the link:

- `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle`
- `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"`
- `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Hobbit lifestyles'`
- `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit lifestyles)`
- `[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"`
- `[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Hobbit lifestyles'`
- `[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Hobbit lifestyles)`

You can place this second part of the link anywhere in your Markdown document. Some people place them immediately after the paragraph in which they appear while other people place them at the end of the document (like endnotes or footnotes).

#### An Example Putting the Parts Together

Say you add a URL as a [standard URL link](#links) to a paragraph and it looks like this in Markdown:

```
In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole](https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"), and that means comfort.
```

Though it may point to interesting additional information, the URL as displayed really doesn't add much to the existing raw text other than making it harder to read. To fix that, you could format the URL like this instead:

```
In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
```

In both instances above, the rendered output would be identical:

> In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to  eat: it was a <a href="https://en.wikipedia.org/wiki/Hobbit#Lifestyle" title="Hobbit lifestyles">hobbit-hole</a>, and that means comfort.

and the HTML for the link would be:

```
<a href="https://en.wikipedia.org/wiki/Hobbit#Lifestyle" title="Hobbit lifestyles">hobbit-hole</a>
```

### Link Best Practices

Markdown applications don't agree on how to handle spaces in the middle of a URL. For compatibility, try to URL encode any spaces with `%20`. Alternatively, if your Markdown application [supports HTML](#html), you could use the `a` HTML tag. 

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Do this</th>
      <th>❌&nbsp; Don't do this</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
        [link](https://www.example.com/my%20great%20page)<br><br>

        &lt;a href="https://www.example.com/my great page"&gt;link&lt;/a&gt;<br><br>
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
        [link](https://www.example.com/my great page)<br><br>
        </code>
      </td>
    </tr>
  </tbody>
</table>

Parentheses in the middle of a URL can also be problematic. For compatibility, try to URL encode the opening parenthesis (`(`) with `%28` and the closing parenthesis (`)`) with `%29`. Alternatively, if your Markdown application [supports HTML](#html), you could use the `a` HTML tag. 

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Do this</th>
      <th>❌&nbsp; Don't do this</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
        [a novel](https://en.wikipedia.org/wiki/<wbr>The_Milagro_Beanfield_War_%28novel%29)<br><br>

        &lt;a href="https://en.wikipedia.org/wiki/<wbr>The_Milagro_Beanfield_War_(novel)"&gt;a novel&lt;/a&gt;<br><br>
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
        [a novel](https://en.wikipedia.org/wiki/<wbr>The_Milagro_Beanfield_War_(novel))
        </code>
      </td>
    </tr>
  </tbody>
</table>
## Image

To add an image, add an exclamation mark (`!`), followed by alt text in brackets, and the path or URL to the image asset in parentheses. You can optionally add a title in quotation marks after the path or URL.

```
![The San Juan Mountains are beautiful!](/assets/images/san-juan-mountains.jpg "San Juan Mountains")
```

The rendered output looks like this:
