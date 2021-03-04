<!DOCTYPE html>
<html>
<head>
<style>
/* This style sets the width of all images to 100%: */
img {
  width: 100%;
}
</style>
</head>
<body>

<h2>Width/Height Attributes or Style?</h2>

<p>The first image uses the width attribute (set to 128 pixels), but the style in the head section overrides it, and sets the width to 100%.</p>

<img src="pic5.jpg" alt="HTML5 Icon" width="64" height="64">

<p>The second image uses the style attribute to set the width to 128 pixels, this will not be overridden by the style in the head section:</p>

<img src="pic5.jpg" alt="HTML5 Icon" style="width:32px;height:32px;">

</body>
</html>
