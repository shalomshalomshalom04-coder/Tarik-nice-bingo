# Tarik-nice-bingo

This repository contains a bingo game (1 to 150 player cards).

This repo now includes a placeholder index.html so GitHub Pages can serve the site. Replace index.html with your game's files or upload your site's build output to the repository root.

How to publish with GitHub Pages

1. Go to Settings → Pages in this repository.
2. Under "Build and deployment" set "Source" to "main" and folder to "/ (root)".
3. Click Save. The site will be published at:
   `https://shalomshalomshalom04-coder.github.io/Tarik-nice-bingo/`

Add a free custom domain (Freenom example)

1. Register a free domain at https://www.freenom.com (choose .tk/.ml/.ga/.cf/.gq).
2. In Freenom DNS settings for your domain set a CNAME record:
   - Host: www
   - Value: `shalomshalomshalom04-coder.github.io`
3. Optionally, add A records for the root domain pointing to GitHub Pages IPs:
   - 185.199.108.153
   - 185.199.109.153
   - 185.199.110.153
   - 185.199.111.153
4. In this repository add a file named `CNAME` with your domain (e.g. `www.example.tk`).
5. In Settings → Pages enter the custom domain and enable HTTPS once the DNS has propagated.

Notes
- Freenom domains can be reclaimed or have renewal issues; consider buying an inexpensive domain for long-term reliability.