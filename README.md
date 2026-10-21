# decompile.tools

Source for [www.decompile.tools](https://www.decompile.tools/), Valentin (VorticonCmdr)'s home for reverse-engineered DOS games, browser tools, and other projects.

## Website

The landing page lives in `index.html`, with its styles and scripts included directly. No build step is required.

To preview it locally, run this command from the repository directory and open <http://localhost:8000>:

```sh
python3 -m http.server 8000
```

Project links such as `/re-Duke/` are served from separate repositories on the live site and are not included in this local preview.

## Hosting

The site is hosted on GitHub Pages with the custom domain `www.decompile.tools`, recorded in `CNAME`.

Keep the repository name `VorticonCmdr.github.io`: it makes this the account's user site, allowing project Pages sites without their own custom domains to inherit `www.decompile.tools/<repository>/`.

## Browser games

- [Duke Nukem](https://www.decompile.tools/re-Duke/)
- [GODS](https://www.decompile.tools/re-gods/)
- [Magic Pockets](https://www.decompile.tools/re-magicpockets/)
- [Micro Machines](https://www.decompile.tools/re-micro-machines/)
- [Pushover](https://www.decompile.tools/pushover/)
- [Lemmings](https://www.decompile.tools/lemmings/)
