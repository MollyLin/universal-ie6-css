<h2>About</h2>
<p>One, standard, universal stylesheet for Internet Explorer 6. Simply copy one of these Conditional Comments into the head of any web page and you're done.</p>

<p><b>Tip:</b> To hide all your other stylesheets from Internet Explorer 6, wrap them inside this Conditional Comment.</p>
```
<!--[if ! lte IE 6]><!-->
/* Stylesheets for browsers other than Internet Explorer 6 */
<!--<![endif]-->
```

<p>Then add the Universal Internet Explorer 6 stylesheet.</p>
```
<!--[if lte IE 6]>
<link rel="stylesheet" href="http://universal-ie6-css.googlecode.com/files/ie6.1.1.css" media="screen, projection">
<![endif]-->
```
<p>If you prefer a light-on-dark version (inspired by Instapaper), use <i>this</i> instead.</p>
```
<!--[if lte IE 6]>
<link rel="stylesheet" href="http://universal-ie6-css.googlecode.com/files/ie6.1.1b.css" media="screen, projection">
<![endif]-->
```

<h2>Previous versions</h2>
<p>1.0</p>
```
<!--[if lte IE 6]>
<link rel="stylesheet" href="http://universal-ie6-css.googlecode.com/files/ie6.1.0.css" media="screen, projection">
<![endif]-->
```
<p>0.3</p>
```
<!--[if lte IE 6]>
<link rel="stylesheet" href="http://universal-ie6-css.googlecode.com/files/ie6.0.3.css" media="screen, projection">
<![endif]-->
```


---


<h2>Status</h2>
<p>Current version: 1.1</p>


---


<h2>Getting started</h2>
<p>Read about this project at <a href='http://stuffandnonsense.co.uk/blog/about/universal_internet_explorer_6_CSS/'>Stuff and Nonsense</a>.</p>