## Say Hello to HTML Elements

``` html

<h1> Hello World! </h1>

```


## Headline with the h2 Element

**h1** elements are often used for main headings while **h2** elements are generally used for subheadings.

``` html

<h2> CatPhotoApp</h2>

```

## Intrdoction to HTML5 Elements

The **main** HTML5 tag helps search engines find the main content of your page:

``` html
<main>
   <h1> Hello World </h1>
   <p> Hello Paragraph </p>
</main>

```

## Add Images to Your Website

``` html
<img src = "https://....." alt = ...>

```

The **alt** attribute is used for screen readers to improve accessibility and is dispalyed iff the smage fiales to load.








## Link to Internal Sections of a page with Anchor Elements

To create an internal link, you assign a link's href attribute to a **hash** symbol plus the value of the **id** for the element that you want to internally link.

Change your external link to an internal link by changing the href attribute to "#footer" and the text from "cat photos" to "Jump to Bottom".

Remove the target="_blank" attribute from the anchor tag since this causes the linked document to open in a new window tab.

Then add an id attribute with a value of "footer" to the <footer> element at the bottom of the page.

``` html

<h2>CatPhotoApp</h2>
<main>

  <a href="#footer" target="_blank">Jump to Bottom</a>

  <img  id = "footer" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.">


</main>

<footer id="footer">Copyright Cat Photo App</footer>

```
## Make Dead Links using Hash Symbol

Sometimes you want to add **a** elemtns to your website before you know where they will link. The **href** attribute can be "#", know as a hash symbol, which is a dead link.


## Create a Text Field

**input** elements are a convenient way to get input from your user.

**input** elements are self-closing.

``` html

<input type = 'text'>

```
