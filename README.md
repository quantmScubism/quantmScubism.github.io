# quantmScubism.github.io
<html lang="en">
<head>
    <meta charset="utf-8">
    <title>Markdown Guide</title>
    <meta name="description" content="A simple guide to writing Markdown.">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>h4 {
            margin-top: 20px;
            margin-bottom: 5px;
        }

        h4 small {
            font-style: italic;
        }

        pre {
            overflow: auto;
            word-wrap: normal;
            white-space: pre;
        }

        footer {
            margin: 20px 0 30px;
            font-size: 80%;
            color: #999;
            text-align: center;
        }</style>
</head>
<body>
<div class="container-fluid">
    <div class="row" style="max-width:500px; margin:auto;">
        <div class="col-xs-12">
            <h1 style="text-align:center;">Markdown Guide</h1>
            <h4>Emphasis</h4>
            <pre>**<strong>bold</strong>**
*<em>italics</em>*
~~<strike>strikethrough</strike>~~</pre>
            <h4>Headers</h4>
            <pre># Big header
## Medium header
### Small header
#### Tiny header</pre>
            <h4>Lists</h4>
            <pre>* Generic list item
* Generic list item
* Generic list item

1. Numbered list item
2. Numbered list item
3. Numbered list item</pre>
            <h4>Links</h4>
            <pre>[Text to display](http://www.example.com)</pre>
            <h4>Quotes</h4>
            <pre>&gt; This is a quote.
&gt; It can span multiple lines!</pre>
            <h4>Images &nbsp;
                <small>Need to upload an image? <a href="http://imgur.com/" target="_blank">Imgur</a> has a great
                    interface.
                </small>
            </h4>
            <pre>![](http://www.example.com/image.jpg)</pre>
            <pre>![Logo](https://myweb.pro.vn/images/logo.jpg =100x100)</pre>
            <h4>Tables</h4>
            <pre>| Column 1 | Column 2 | Column 3 |
| -------- | -------- | -------- |
| John     | Doe      | Male     |
| Mary     | Smith    | Female   |

<em>Or without aligning the columns...</em>

| Column 1 | Column 2 | Column 3 |
| -------- | -------- | -------- |
| John | Doe | Male |
| Mary | Smith | Female |
</pre>
            <h4>Displaying code</h4>
            <pre>`var example = "hello!";`

<em>Or spanning multiple lines...</em>

```
var example = "hello!";
alert(example);
```</pre>
        </div>
    </div>
</div>



</body>
</html>
