
1. Everything goes inside head tag will not render to user
2. information inside the head tag is used by browser for diffrent purpose 
  a. idenetifying char type (UTF-8)
  b. mobile resopisve ot nnot (viewport)
  c. search engine optimzation like 
  d. also used for linking external files, like css file js file


1. Essentila Tag 
  <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Page Title</title>
</head>
These three should be on every page, always.

2. SEO & Social

<meta name="description" content="A short summary of the page.">
<meta name="keywords" content="html, web, tutorial">
<meta name="author" content="John Doe">

<!-- Open Graph (Facebook, LinkedIn previews) -->
<meta property="og:title" content="My Page">
<meta property="og:description" content="Page summary">
<meta property="og:image" content="https://example.com/image.jpg">

<!-- Twitter card -->
<meta name="twitter:card" content="summary_large_image">

3. Linking external files3
<!-- CSS stylesheet -->
<link rel="stylesheet" href="styles.css">

<!-- Favicon (icon in browser tab) -->
<link rel="icon" href="favicon.ico" type="image/x-icon">

<!-- Web font (e.g. Google Fonts) -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Inter&display=swap" rel="stylesheet">

4. Inline styles vs external

<!-- Inline (small projects or overrides) -->
<style>
  body { margin: 0; font-family: sans-serif; }
</style>

<!-- External is preferred for larger projects -->
<link rel="stylesheet" href="styles.css">


5. Performance hints5
<!-- Load a resource early -->
<link rel="preload" href="hero.jpg" as="image">

<!-- Connect to a domain early -->
<link rel="preconnect" href="https://api.example.com">

<!-- Load script without blocking page render -->
<script src="app.js" defer></script>
<script src="analytics.js" async></script>

defer — runs after HTML is parsed, in order
async — runs as soon as downloaded, out of order




<meta charset="UTF-8"> — sets character encoding so special characters (é, ñ, €) display correctly
<meta name="viewport" ...> — makes the page responsive on mobile devices
<title> — the text shown in the browser tab and search engine results
<link rel="stylesheet"> — where you'd link an external CSS file
<meta name="description"> — optional, but good for SEO