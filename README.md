## Basic Instructions
1. Place the files into the root directory of your website/project
2. Add the manifest in the `<head>` your **index.html** file -- `<link rel="manifest" href="manifest.json" />`
3. Add the `app.js` file to your **index.html** -- `<script src="app.js"></script>`
4. Get some icons for your PWA, place them somewhere in the project directory, and add them to your **manifest.json** ([Try this tool](https://tools.crawlink.com/tools/pwa-icon-generator/))
5. Bob's your uncle

**NOTE: Make sure your site uses HTTPS or it won't be installable as a PWA!**

## For iPhones
Add the following to your **index.html** `<head>` as well for the PWA to work on iPhones!
```
<link rel="apple-touch-icon" href="images/icons/icon-72x72.png" />
<link rel="apple-touch-icon" href="images/icons/icon-96x96.png" />
<link rel="apple-touch-icon" href="images/icons/icon-128x128.png" />
<link rel="apple-touch-icon" href="images/icons/icon-144x144.png" />
<link rel="apple-touch-icon" href="images/icons/icon-152x152.png" />
<link rel="apple-touch-icon" href="images/icons/icon-192x192.png" />
<link rel="apple-touch-icon" href="images/icons/icon-384x384.png" />
<link rel="apple-touch-icon" href="images/icons/icon-512x512.png" />
<meta name="apple-mobile-web-app-status-bar" content="#000000" />
<meta name="theme-color" content="#000000" />
```
