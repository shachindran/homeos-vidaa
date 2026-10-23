# HomeOS — Cinema Edition v3

A personal, ad-free **dashboard page** for Hisense VIDAA built-in browsers. Not a VIDAA firmware replacement, Google Chrome, or a native app launcher. NOT affiliated with Apple, Hisense, or the streaming services.

## Deploy free with GitHub Pages
1. Create a PUBLIC GitHub repo called `homeos-vidaa` at https://github.com/new and check Add a README.
2. Download this zip, unzip it on your Mac.
3. Open the repository on GitHub, click **Add file > Upload files**, then drag **index.html** and the **assets** folder (the contents of the project folder, not the enclosing folder) to the upload page.
4. Commit changes.
5. Go to **Settings > Pages > Build and deployment > Source: Deploy from a branch > Branch: main > Folder: /(root) > Save**.
6. Open `https://YOUR-GITHUB-USERNAME.github.io/homeos-vidaa/` in your Hisense VIDAA browser.

## Behaviour
- Native app tiles are **visual shortcuts** only: due to VIDAA browser restrictions, these display instructions to press Home on the TV remote and open the app from VIDAA.
- Music, search, and legal streaming websites are direct browser links; their websites may not support video/audio playback in the TV browser.
- `Cinema.watch`, `Tamilgun`, and `Tamildhool` are **unconfigured** personal bookmark tiles. Press OK, enter an exact HTTPS destination you trust. HomeOS stores it in your browser's local storage. Bookmark addresses are NOT supplied and may disappear if browsing data is cleared. Only open sites you have the right to access.
- Website logos: popular brand outlines are packaged locally from the Simple Icons icon set. Some other service logos load as actual favicons from Google's favicon service. If unavailable, the tile remains readable by its text label. These may not be identical to the official TV-app icons.
- The ad-free promise applies only to this dashboard. HomeOS does NOT block ads on third-party sites, streaming services, or the native VIDAA home screen.
- Keep your TV updated, and don't provide payment details to unverified sites. No untrusted DNS hijacks or privileged installation are required.

## Performance
Static HTML, CSS, tiny JS, optimized 189KB wallpaper, seven bundled brand SVGs. No background video, analytics, tracking, external JS, font downloads, or background network requests except favicons from Google.

## Testing
Desktop browser tested; actual Hisense TV performance and remote key mapping must be verified by you.
