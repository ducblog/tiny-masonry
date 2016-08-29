# tiny-masonry
Tiny masonry grid in vanilla JavaScript.
http://www.cssscript.com/tiny-masonry-like-javascript-grid-library-tiny-masonry-js/

<p>tiny-masonry.js is a minimalist JavaScript library that makes it easy to create Masonry-like responsive, neat, fluid grid layout for your web project.</p>
<h2>How to use it:</h2>
<p>Just include the tiny.masonry.js script on the webpage and you&#8217;re ready to go.</p>
<pre class="brush:xml">&lt;script src="tiny-masonry.min.js"&gt;&lt;/script&gt;</pre>
<p>Add your items to the grid.</p>
<pre class="brush:xml">&lt;div class="grid"&gt;
  &lt;div class"gridItem"&gt;Item 1&lt;/div&gt;
  &lt;div class"gridItem"&gt;Item 2&lt;/div&gt;
  &lt;div class"gridItem"&gt;Item 3&lt;/div&gt;
  &lt;div class"gridItem"&gt;Item 4&lt;/div&gt;
  ...
&lt;/div&gt;</pre>
<p>Set the width of the grid items.</p>
<pre class="brush:css">.gridItem {
  width: 50%;
}</pre>
<p>Initialize the grid.</p>
<pre class="brush:javascript">var grid = document.querySelector(".grid")
new TinyMasonry(grid)</pre>
