---
title: Typography
author:
    username: admin
    alias: RocketTheme
date: '2016-01-01 00:00:01'
published: true
publish_date: '2016-10-04 19:25:39'
taxonomy:
    category: 'Theme Features'
process:
    markdown: true
    twig: false
markdown:
    extra: true
---

##Typography

Helium comes with a robust set of typography options that you can use to bring your content to life. In this page, we will list and give examples of the many typography options you can use.

# Variations

<p>Variations are classes that can be applied inline, as well as put to use in some particles through **Variations** or applied directly to content as CSS classes.</p>

## Buttons

Buttons have a number of great variations to choose from. You should note that in the HTML breakdown we have added a `button` class in addition to the variation, which is a requirement for these particular variations to work. You can also combine these variations.

[Default Button](#) {.button} &nbsp; [Button Bevel](#) {.button .button-bevel} &nbsp; [Button Square](#) {.button .button-square}

<pre>&#x3C;a href=&#x22;#&#x22; class=&#x22;button&#x22;&#x3E;Default Button&#x3C;/a&#x3E;
&#x3C;a href=&#x22;#&#x22; class=&#x22;button button-bevel&#x22;&#x3E;Button Bevel&#x3C;/a&#x3E;
&#x3C;a href=&#x22;#&#x22; class=&#x22;button button-square&#x22;&#x3E;Button Square&#x3C;/a&#x3E;</pre>

[Button 2](#) {.button .button-2}

<pre>&#x3C;a href=&#x22;#&#x22; class=&#x22;button button-2&#x22;&#x3E;Button 2&#x3C;/a&#x3E;</pre>

[Button Outline](#) {.button .button-outline}

<pre>&#x3C;a href=&#x22;#&#x22; class=&#x22;button button-outline&#x22;&#x3E;Button Outline&#x3C;/a&#x3E;</pre>

[Button Gradient](#) {.button .button-gradient}

<pre>&#x3C;a href=&#x22;#&#x22; class=&#x22;button button-gradient&#x22;&#x3E;Button Gradient&#x3C;/a&#x3E;</pre>

[Button Block](#) {.button .button-block}

<pre>&#x3C;a href=&#x22;#&#x22; class=&#x22;button button-block&#x22;&#x3E;Button Block&#x3C;/a&#x3E;</pre>

[Button xlarge](#) {.button .button-xlarge}

<pre>&#x3C;a href=&#x22;#&#x22; class=&#x22;button button-xlarge&#x22;&#x3E;Button XLarge&#x3C;/a&#x3E;</pre>

[Button Large](#) {.button .button-large}

<pre>&#x3C;a href=&#x22;#&#x22; class=&#x22;button button-large&#x22;&#x3E;Button Large&#x3C;/a&#x3E;</pre>

[Button Small](#) {.button .button-small}

<pre>&#x3C;a href=&#x22;#&#x22; class=&#x22;button button-small&#x22;&#x3E;Button Small&#x3C;/a&#x3E;</pre>

[Button Xsmall](#) {.button .button-xsmall}

<pre>&#x3C;a href=&#x22;#&#x22; class=&#x22;button button-xsmall&#x22;&#x3E;Button XSmall&#x3C;/a&#x3E;</pre>

# Headings

All HTML headings, `<h1>` through `<h6>` are available.

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

# Notice Styles
<p class="alert alert-success">Nullam quis risus eget urna mollis ornare vel eu leo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>
<pre>&lt;p class="alert alert-success"&gt;&hellip;&lt;/p&gt;</pre>
<p class="alert alert-info">Nullam quis risus eget urna mollis ornare vel eu leo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>
<pre>&lt;p class="alert alert-info"&gt;&hellip;&lt;/p&gt;</pre>
<p class="alert alert-warning">Nullam quis risus eget urna mollis ornare vel eu leo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>
<pre>&lt;p class="alert alert-warning"&gt;&hellip;&lt;/p&gt;</pre>
<p class="alert alert-error">Nullam quis risus eget urna mollis ornare vel eu leo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>
<pre>&lt;p class="alert alert-error"&gt;&hellip;&lt;/p&gt;</pre>


# Blockquotes
For quoting blocks of content from another source within your document.

### Default blockquote

<p>Wrap <code>&lt;blockquote&gt;</code> around any <abbr title=
"HyperText Markup Language">HTML</abbr> as the quote. For straight quotes we
recommend a <code>&lt;p&gt;</code>.</p>


> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.

<pre>&lt;blockquote&gt;
&lt;p&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.&lt;/p&gt;
&lt;/blockquote&gt;</pre>

### Blockquote options

Style and content changes for simple
variations on a standard blockquote.

#### Naming a source

<p>Add <code>&lt;small&gt;</code> tag for identifying the source. Wrap the name
of the source work in <code>&lt;cite&gt;</code>.</p>
<blockquote>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere
    erat a ante.</p><small>Someone famous in <cite title="Source Title">Source
    Title</cite></small>
</blockquote>
<pre>&lt;blockquote&gt;&lt;p&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.&lt;/p&gt;&lt;small&gt;Someone famous &lt;cite title="Source Title"&gt;Source Title&lt;/cite&gt;&lt;/small&gt;&lt;/blockquote&gt;</pre>


<div class="g-grid">
    <div class="g-block">
        <div class="g-content nomargintop nopaddingtop">
            <h1>Code</h1>
            <h4>Inline</h2>
            <p>Wrap inline snippets of code with <code>&lt;code&gt;</code>.</p>
            For example, <code>&lt;section&gt;</code> should be wrapped as inline.
<pre>For example, &lt;code&gt;&lt;section&gt;&lt;/code&gt; should be wrapped as inline.</pre>
            <p><strong>Note:</strong> Be sure to keep code within <code>&lt;pre&gt;</code> tags as close to the left as possible; it will render all tabs.</p>
        </div>
    </div>
    <div class="g-block">
        <div class="g-content nomargintop nopaddingtop">
            <h2 class="nomargintop">&nbsp;</h2>
            <h4>Basic block</h2>
                <p>Use <code>&lt;pre&gt;</code> for multiple lines of code. Be sure to escape any angle brackets in the code for proper rendering.</p>
<pre>&lt;p&gt;Sample text here&hellip;&lt;/p&gt;</pre>
<pre>&lt;pre&gt;&amp;lt;p&amp;gt;Sample text here&hellip;&amp;lt;/p&amp;gt;&lt;/pre&gt;</pre>
        </div>
    </div>
</div>

# Tables

<span>#</span>|First Name|Last Name|Username
-|----------|---------|--------
1|John         |  Doe      | JohnDoe
2|Jane         |  Doe      | JaneDoe
3|Bob         |  Doe      | BobDoe

<pre>&lt;table class="table"&gt;&hellip;&lt;/table&gt;</pre>
