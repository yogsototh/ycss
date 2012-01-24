# y.css

This is a very clean CSS to start with.

You have some typography classes for small caps for example.

Typically: 

- the right size of the content.
- header numbering inside article, 
- nice link (no underline, but a sup cross)

A typical HTML to use would be:

<pre>
&lt;html&gt;
    &lt;head&gt;
        &lt;meta http-equiv="Content-Type" content="text/html; charset=UTF-8" /&gt;
        &lt;link rel="stylesheet" type="text/css" href="y.css" /&gt;
        &lt;title&gt;Page title&lt;/title&gt;
    &lt;/head&gt;
    &lt;body&gt;
        &lt;header&gt;
            &lt;h1&gt;Title&lt;/h1&gt;
            &lt;h2&gt;Subtitle&lt;/h2&gt;
        &lt;/header&gt;

        &lt;article&gt;
            &lt;title&gt; &lt;h1&gt;Article Title&lt;/h1&gt; &lt;/title&gt;
            &lt;p&gt;This is the article&lt;/p&gt;
            &lt;h2&gt;section&lt;/h2&gt;
            &lt;h3&gt;subsection&lt;/h3&gt;
            &lt;p&gt;Some &lt;em&gt;content&lt;/em&gt; &lt;strong&gt;with&lt;/strong&gt; &lt;a href="#"&gt;a link&lt;/a&gt;. &lt;/p&gt;
            &lt;blockquote&gt;A blockquote&lt;/blockquote&gt;
        &lt;/article&gt;

        &lt;footer&gt;
        &lt;p&gt;Footer content&lt;/p&gt;
        &lt;/footer&gt;
    &lt;/body&gt;
&lt;/html&gt;
</pre>
