# HashCheck — Local SHA-256

A browser utility to calculate SHA-256 digests for text or local files and compare a file digest to a provided expected value.

## Try it

Open the GitHub Pages HTTPS address (or localhost). Choose or drop a file up to 50 MB, optionally paste an expected 64-character hexadecimal digest, and select **Compare**. Or enter text and calculate its digest. Uses the browser Web Crypto API.

Selected files and text remain in the browser. A matching digest confirms equality with the digest you supplied; it does not establish the publisher's identity or make an untrusted source safe.

## GitHub Pages

Upload `index.html` and this README to a public repository. In **Settings → Pages**, publish from the `main` branch and `/ (root)`. The deployed site must use HTTPS for Web Crypto.
