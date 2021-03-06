
### HTML

Declaritive language

<elementname attribute="">
    
Structuring content
* main
main content , only 1
* header
content at header
* footer
content at footer
* article
wrap around any instance of an article
* section
wrap section around content
* aside
marks content that is off to side or not main attraction 
    
### Head tag

* card on google
```
<head>
    <meta name="description" content="A description of this site that will show up in search engine results.">
    <link href="main.css" rel="stylesheet">
    <script src="_.js"></script>
</head>
```



### Header tag 
```
<header></header>
```
### Nav tag

```
<header>
    <nav></nav>
</header>
```

```
<nav role="navigation" aria-label="main menu">
    <ul class="navbar">
        <li><a href="/">Home</a></li>
        <li><a href="/people">People</a></li>
        <li><a href="/prices">Prices</a></li>
        <li><a href="/contact">Contact</a></li>
    </ul>
</nav>
```


### Main tag , Footer tag
```
<main>
    <header>
        <h1>Types of Sports</h1>
    </header>
    <article>
        <h3>Baseball</h3>
        <p>
        The first game of baseball was played in Cooperstown, New York in the summer of 1839.
        </p>
    </article>
</main>
```
```
<header>

</header>
<main>

</main>
```

<body>
    <header>
    </header>
    <main>
    </main>
    <footer>
    </footer>
</body>

### Article tag , section tag 

* <section> defines elements in a document, such as chapters, headings, or any other area of the document with the same theme

* The <article> element holds content that makes sense on its own. <article> can hold content such as articles, blogs, comments, magazines,



```
<section>
  <h2>Fun Facts About Cricket</h2>
  <article>
    <p>A single match of cricket can last up to 5 days.</p>
  </article>
</section>
```

### Aside tag 

<aside> element is used to mark additional information that can enhance another element but isn’t required in order to understand the main content. This element can be used alongside other elements such as <article> or <section>

* Bibliographies
* Endnotes
* Comments
* Pull quotes
* Editorial sidebars
* Additional information

```
<aside>
  <p>
   Babe Ruth once stated, “Heroes get remembered, but legends never die.” 
  </p>
</aside>```

### figure tag 

<figure> is an element used to encapsulate media such as an image, illustration, diagram, code snippet, etc, which is referenced in the main flow of the document.

```
<figure>
  <img src="overwatch.jpg"/>
</figure>
```

add a caption to the image by using <figcaption>.
<figcaption> is an element used to describe the media in the <figure> tag. Usually, <figcaption> will go inside <figure>

```
<figure>
  <img src="overwatch.jpg">
  <figcaption>This picture shows characters from Overwatch.</figcaption>
</figure>
```



### Audio , Attributes tag 

```
<audio autoplay controls>
  <source src="iAmAnAudioFile.mp3" type="audio/mp3">
</audio>
```

### Video embed tag ,

* controls: When added in, a play/pause button will be added onto the video along with volume control and a fullscreen option.
* autoplay: The attribute which results in a video automatically playing as soon as the page is loaded.
* +loop: This attribute results in the video continuously playing on repeat.

```
<video src="coding.mp4" controls>Video not supported</video>

```
Another tag that can be used to incorporate media content into a page is the <embed> tag, which can embed any media content including videos, audio files, and gifs from an external source

```
<embed src="download.gif"/>
```

### Quote tag

<blockquote><p></p></blockquote> //block
<q></q> // inline 
<cite></cite>

* attribute 
  * contenteditable = "true"

### time 

<time></time>
<time datetime="YYYY-MM-DD"></time>

### show code

<code>&lt;H4</code>

### <br> , <pre>
spacing , line break
show indentation


### subscript , superscript

<sub></sub>
<sup></sup>

mathml

<small></small>

### Entity


&copy;
&trade;
&star;
&nbsp; // dont break

### image
```
<img src="https://_.jpg" alt=" " width="500" height="400">

<img src="https:// "
    alt=" "
    width=" "
    height=" "
    srcset="
        https:// dog-960.jpg  2x,
        https:// dog-1440.jpg 3x,
        https:// dog-1920.jpg 4x">
        
<img src="https:// dog-960.jpg"
    alt=" "
    width=" "
    height=" "
    srcset="
        https:// dog-960.jpg  960w,
        https:// dog-1440.jpg 1440w,
        https:// dog-1920.jpg 1920w"
    sizes="
        (max-width: 480px) 240px,
        (max-width: 960px) 480px,
        (max-width: 1440px) 960px,
        1920px"
        >        

<picture>
    <source media="(min-width:600px)"
        srcset="https:// dog2-320.jpg 320w,
                https:// dog2-480.jpg 480w">
    
    <source srcset="https://    dog2-cropped-320.jpg 320w,
                    https://    dog2-cropped-480.jpg 480w">
    
    <img src="https:// .jpg"
        alt=" "
        height="360px"
        width="480px">
    
</picture>

<figure>
    <img src="" height="" alt="" >
    
    <figcaption>
    </figcaption>
</figure>
```
