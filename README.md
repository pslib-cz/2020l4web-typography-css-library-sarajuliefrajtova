# TYPOGRAPHY CSS LIBRARY #
**Author:** *Sara Julie Frajtova*
## Demo site
Link to **[demo](http://sarajuliefrajtova.github.io/typography/)** site for preview.
## Dependecies
``` 
<link rel="stylesheet" href="./style/normalize.css">
``` 
## Implementation
``` 
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./style/style.css">
    <link rel="stylesheet" href="./style/typhography.css">
    <link rel="stylesheet" href="./style/queries.css">
    <link rel="stylesheet" href="./style/normalize.css">
    <title>CCS typografická knihovna</title>
</head>
``` 
## Usage
This library is recommended for a blog posts pages use. CSS files are primarly based on styling HMTL tags such as ```<section>```,  ```<h1>, <h2>``` etc.:
- ol/ul, li
- blockquote
- p, a
- h1 (**not** part of an section), h2, h3, h4, h5, h6


There are also some components which can be initialized by classes - e.g. ``` .wrapper ```. To ``` .wrapper ``` class is assigneted a certain **max-width** that gives "natural" margin to whole page. The ``` .wrapper ``` should be applied on ``` <div> ``` tag, with the following structure: 

``` 
<main>
    <article>
        <div class="wrapper">
            <h1>1st heading</h1>
            <ul class="post-info">
                <li>Author: <span>Lorem ipsum</span></li>
                <li>Date: <span>DD. MM. YYYY</span></li>
            </ul>
            <figure>
                <img src="https://via.placeholder.com/1000x500" alt="img" class="welcome-img">
                <figcaption>Lorem ipsum dolor sit amet consectetur adipisicing elit.</figcaption>
            </figure>
            <section>
                <h2>2nd heading</h2>
                .
                .
                .
            </section>
         </div>
     </article>
</main>
```
There is also ```.post-info``` **class** which can be used for ***author name*** or ***date*** of posting the article.
## Components

### Header 
If you want, you can even use the ```<header> ``` section with the following ```.nav-bar``` class. 
``` 
 <header>
        <nav class="nav-bar">
            <ul>
                <li><a href="#">Logo</a></li>
                <li><a href="#">2nd item</a></li>
                <li><a href="#">3rd item</a></li>
            </ul>
        </nav>
    </header>
``` 

### Section, heading (***h2***) and paragraph in an article 
``` 
<section>
    <h2>2nd heading</h2>
    <p>
       Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet ea debitis suscipit, quia pariatur reprehenderit nesciunt at quam adipisci nobis libero                sapiente assumenda distinctio modi facilis, doloribus deleniti iusto qui. Lorem ipsum dolor sit amet consectetur adipisicing elit. Facere, alias cum? Magni          quasi voluptatum velit modi consequatur, excepturi assumenda aliquam cum pariatur quidem, quo veritatis earum nulla officiis porro corporis!
    </p>
</section>
``` 

### Lists 
``` 
 <ul>
    <li>Lorem ipsum dolor sit amet consectetur adipisicing elit.</li>
    <li>Lorem ipsum dolor sit amet consectetur adipisicing elit.</li>
    <li>Lorem ipsum dolor sit amet consectetur adipisicing elit.</li>
    <li>Lorem ipsum dolor sit amet consectetur adipisicing elit.</li>
</ul>
``` 
``` 
<ol>
    <li>Lorem ipsum dolor sit amet consectetur adipisicing elit.</li>
    <li>Lorem ipsum dolor sit amet consectetur adipisicing elit.</li>
    <li>Lorem ipsum dolor sit amet consectetur adipisicing elit.</li>
    <li>Lorem ipsum dolor sit amet consectetur adipisicing elit.</li>
</ol>
``` 
### Images in a post
``` 
<figure>
    <img src="#" alt="img" class="welcome-img">
    <figcaption>Lorem ipsum dolor sit amet consectetur adipisicing elit.</figcaption>
</figure>
``` 
### Footer in a post
``` 
    </main>

    <footer>

        <ul>
            <li><a href="#">INSTAGRAM</a></li>
            <li><a href="#">FACEBOOK</a></li>
            <li><a href="#">TWITTER</a></li>
        </ul>

        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Possimus expedita nostrum reiciendis eaque
            doloribus repellendus incidunt, eius vitae accusamus tenetur illo facere vel. Officiis maxime
            exercitationem architecto laudantium aut repellendus.</p>
    </footer>
</body>

</html>
``` 

