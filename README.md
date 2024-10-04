## Embed Blocker

Block others ability to embed or iframe your website on client side.

## How it works

It basically checks if the page is in an iframe or similar element instead of the origin. If yes (the page is in an iframe), redirect to /blocked or the given url. If no (the page is not in an iframe) show the index.html.

## How to install

Just pop the script into your &lt;head&gt; tag located in this repositorys index.html and change the "blocked page" url to yours, or keep it the same.

## Test it yourself

<a href="https://szeccsa.github.io/embed-blocker" target="_blank">Demo</a>

<a href="https://www.iframe-generator.com" target="_blank">Iframe generator</a>

Just pop the "https://szeccsa.github.io/embed-blocker" address into the "iFrameURL:" field on Iframe generator, press the "Generate" and then the "Preview" button.
