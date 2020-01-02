# UTMDSC-Web-101
By Henry Tu

## Demo Pages

[Hello World!](https://henrytwo.github.io/UTMDSC-Web-101/step-1-helloworld) <br>
[HTML Tags](https://henrytwo.github.io/UTMDSC-Web-101/step-2-tags) <br>
[CSS](https://henrytwo.github.io/UTMDSC-Web-101/step-3-css) <br>
[Bootstrap](https://henrytwo.github.io/UTMDSC-Web-101/step-4-bootstrap) <br>

## Bread and Butter
There are 3 main components to a website (frontend).

HTML - The backbone / skeleton<br>
CSS - The style and formatting<br>
JS - The logic (and actual code)

## Creating an HTML Page

### Comments
```
<!-- Comments go in here-->

<!-- 
Multiline comment
Line 1
Line 2
-->

```

### How tags work
Replace `X` with the name of the tag. Be sure to close any tags that you open! 
```$xslt
<X>  <!-- Open tag -->
     <!-- Stuff goes inside -->
</X> <!-- Close tag -->
```

### Sample Page
```
<html lang="en">
<head>                           <!-- Contains meta data (stuff that isn't displayed) -->
    <meta charset="UTF-8">
    <title>Hello, world!</title> <!-- Title that will be displayed on top -->
</head>

<body>                           <!-- The actual content of the website -->
This is a cool website.
</body>
</html>
```

### Basic text
```$xslt
<p>
    This is a paragraph
</p>

<h1>
    BIG TEXT
</h1>

<h2>
    LESS BIG TEXT
</h2>

<h3>
    LESS BIG TEXT
</h3>

<h4>
    SMOL TEXT
</h4>

<h5>
    SMOLLER TEXT
</h5>
```

### Hyperlinks
You can use  `a` tags to direct users to another page. 
```$xslt
<a src="https://google.com">
    <!-- What you want to be clicked goes here -->
    
    Go to Google!
</a>
```

Add ``target="_blank"`` to the `a` tag to make it open in a new tab.
```$xslt
<a src="https://google.com" target="_blank">
    <!-- What you want to be clicked goes here -->
    
    Go to Google!
</a>
```

### Images
You can use `img` tags to add images to your website! Put the path to your desired image in `src=""`
```$xslt
<img src="https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png">
</img>
```

### Linking CSS
It's good practice to put CSS in a different file so that your code doesn't become super cluttered. Put the path to your CSS file in `href=""`.


``    <link href="css/main.css" rel="stylesheet">
``

### Scale on mobile properly
Add this to make sure your website scales on mobile properly.

```<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=0" />```

### Bootstrap
Bootstrap is a popular framework for frontend web projects. Why make something from scratch when it already exists?
<br>
<br>
To install bootstrap, add the following in your `<head>`.


<br>

<figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;link</span> <span class="na">rel=</span><span class="s">"stylesheet"</span> <span class="na">href=</span><span class="s">"https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"</span> <span class="na">integrity=</span><span class="s"><span>"<span class="corInf sha384" data-title="sha384" data-code="sha384">sha<b></b>384</span>-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T"</span></span> <span class="na">crossorigin=</span><span class="s">"anonymous"</span><span class="nt">&gt;</span></code></pre></figure>


<br>
<br>

<pre><code class="language-html" data-lang="html"><span class="nt">&lt;script </span><span class="na">src=</span><span class="s">"https://code.jquery.com/jquery-3.3.1.slim.min.js"</span> <span class="na">integrity=</span><span class="s"><span>"<span class="corInf sha384" data-title="sha384" data-code="sha384">sha<b></b>384</span>-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"</span></span> <span class="na">crossorigin=</span><span class="s">"anonymous"</span><span class="nt">&gt;&lt;/script&gt;</span>
<span class="nt">&lt;script </span><span class="na">src=</span><span class="s">"https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"</span> <span class="na">integrity=</span><span class="s"><span>"<span class="corInf sha384" data-title="sha384" data-code="sha384">sha<b></b>384</span>-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1"</span></span> <span class="na">crossorigin=</span><span class="s">"anonymous"</span><span class="nt">&gt;&lt;/script&gt;</span>
<span class="nt">&lt;script </span><span class="na">src=</span><span class="s">"https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"</span> <span class="na">integrity=</span><span class="s"><span>"<span class="corInf sha384" data-title="sha384" data-code="sha384">sha<b></b>384</span>-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM"</span></span> <span class="na">crossorigin=</span><span class="s">"anonymous"</span><span class="nt">&gt;&lt;/script&gt;</span></code></pre>

<br>

Here's some documentation to help you get started: <br>

[Bootstrap Documentation](https://getbootstrap.com/docs/4.3/getting-started/introduction/)
