Pulpit Clock — offline install

1. Go to https://app.netlify.com/drop in a browser.
2. Drag this whole ZIP file onto the page. No account needed to get a link;
   make one (free) if you want to keep the address permanently.
3. Netlify gives you a URL. Open it in Safari on your iPhone.
4. Tap Share, then "Add to Home Screen".

Open it once with a connection. After that it runs with the network off,
in airplane mode, anywhere.

To change the app later: edit index.html, change CACHE = "pulpit-clock-v1"
in sw.js to "pulpit-clock-v2", and re-upload. Otherwise phones keep
serving the old copy from cache.

Typeface is Archivo by Omnibus-Type, SIL Open Font License 1.1, embedded
in index.html so nothing loads from Google.
