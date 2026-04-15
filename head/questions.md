1. What is the purpose of the <head> element?

It contains metadata about the page — information the browser needs but doesn't display to the user. This includes character encoding, page title, CSS links, scripts, and SEO information.


2. What are the three essential tags every <head> should have?

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Page Title</title>
Charset for encoding, viewport for mobile responsiveness, title for the browser tab.

3. What does <meta charset="UTF-8"> do? What happens without it?

It tells the browser how to decode the bytes of the HTML file. UTF-8 supports almost every character in the world. Without it, special characters like é, ñ, €, or Chinese/Arabic text may display as garbled symbols like â€™


4. What does the <title> tag affect?
Three things:

Text shown in the browser tab
Text shown in search engine results (Google)
Default name when bookmarking the page

5. What is a favicon and how do you add one?
A favicon is the small icon shown in the browser tab next to the title

<link rel="icon" href="favicon.ico" type="image/x-icon">

<!-- Modern approach (PNG) -->
<link rel="icon" href="/favicon.png" type="image/png">

<!-- Apple devices -->
<link rel="apple-touch-icon" href="/apple-icon.png">