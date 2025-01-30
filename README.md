## Basic Instructions
1. Click the **Use this template** button, or clone this repo, or download the files `manifest.json`, `app.js` and `sw.js`
2. Make sure `manifest.json`, `app.js` and `sw.js` are in your project's root
3. Add the manifest in the `<head>` of your **index.html** file -- `<link rel="manifest" href="manifest.json" />`
4. Add the `app.js` script to your **index.html** -- `<script src="app.js"></script>`
5. Get some icons for your PWA, place them somewhere in the project directory, and add them to your **manifest.json** ([This tool may help](https://www.pwabuilder.com))
7. Bob's your uncle, check out the [demo](https://pwa-template.surge.sh) to see it in action

**NOTE: Make sure your site uses HTTPS or it won't be installable as a PWA!** Free web hosts like [Netlify](https://netlify.com), [Vercel](https://vercel.com), [Cloudflare Pages](https://pages.cloudflare.com) and [Surge](https://surge.sh) should let you deploy with HTTPS for free, with minimal or zero config.

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
