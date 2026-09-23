# Add PolyTrack to Google Sites

Google Sites does not run JavaScript pasted directly into a page. Use the
provided iframe embed, which loads the game from jsDelivr instead of GitHub
Pages.

1. Push the repository to GitHub and make sure it is public so jsDelivr can
   read the files.
2. Open [google-sites-embed.html](google-sites-embed.html) and copy its
   complete contents.
3. In Google Sites, choose **Insert > Embed > Embed code** and paste the
   contents of [google-sites-embed.html](google-sites-embed.html).
4. Resize the embed to a wide landscape area. A height of at least 480px is
   recommended for the game controls.

The game and its assets remain in the repository, so relative asset paths,
Web Workers, and the physics WASM module continue to work inside the iframe.