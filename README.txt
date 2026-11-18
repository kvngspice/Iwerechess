OLU OF WARRI CHESS SET: WEBSITE WITH AR

Put the site online (easiest way, free, about 2 minutes)
1. On a laptop, go to https://app.netlify.com/drop
2. Drag this whole folder onto the page.
3. Netlify gives you a web address. Open it on your phone.
4. Tap "View on your table" to see the set in AR.
   (Create a free Netlify account when asked if you want the address to stay online.)

AR works on:
- iPhone and iPad (Safari): opens in Apple's AR viewer
- Android phones with Google Play Services for AR: opens in Google's AR viewer
On a computer the AR page shows a QR code: scan it with your phone.

Files
- index.html      the chess app (Explore, Learn, Play)
- ar.html         the AR page
- set.glb         the set for Android and the 3D preview
- set.usdz        the set for iPhone
- _headers        tells Netlify how to serve the AR files (keep it)
- vercel.json     the same, if you use Vercel instead of Netlify
- *.txt, map.png, stockfish.js   models, board map and chess engine used by the app

AR needs a real https address. It will not work from a file opened on your computer
or inside the Claude artifact link.
