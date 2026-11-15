# Basharat Wani — basharatwani.com

Personal website of Basharat Wani — Senior Engineering Director at Microsoft, working in the Microsoft CISO security organization building and protecting Microsoft's Crown Jewels. Live at https://basharatwani.com.

## What's on the site
- Opening story: a builder narrative across Microsoft, AWS, and Rackspace
- Career: Microsoft (current role and an earlier stint), AWS, Ascensus, Rackspace, ZeniMax Online Studios
- Outdoors: hike cards
- Writing: his 2010–2024 blog, described in past tense (no live blog address)
- Latest tweets

## Tech
A single self-contained `index.html`, hosted on GitHub Pages. Custom domain via Squarespace DNS, HTTPS enforced. The repo contains `CNAME`, `index.html`, and this README.

## Updating the site
1. Edit the page (or its source in Muse) and export a fresh `index.html`.
2. Delete the old `index.html`, upload the new file, and rename it to `index.html` inside a GitHub Codespace with `git mv` — the web editor's rename corrupts large files, so never use it for `index.html`.
3. Commit directly to `main`; GitHub Pages publishes automatically. Verify the live page after each deploy.

## Career highlights
- Ascensus: grew the software engineering team from 90 to 240 engineers; scaled releases from 30 to 460 per year within 18 months.
- Rackspace: took the Cloud Apps portfolio (Email and Apps) from $22M to $70M in revenue.
- AWS: Senior Engineering Leader; data center capacity planning and demand across ~800 data centers.
