# Root Faction Overview Site

This repository contains the source code for "The Factions of Root", a static website that provides a simple overview of the playable factions in the board game Root from [Leder Games](https://ledergames.com/).

## Developing

### Prerequisites

This site is built with [Zola](https://www.getzola.org/), a static-site generator written in Rust. To install Zola, follow the instructions on their [Installation](https://www.getzola.org/documentation/getting-started/installation/) page. This site was built with Zola version 0.22.1.

### Making changes

Start by cloning the repository:
```
git clone https://github.com/chris-t-jansen/root-factions-site
cd root-factions-site
```

Then, with Zola installed, you can start a server for local development:
```
zola serve
```

This will start a web server that uses port 1111 by default, so you can view the site in your browser at the URL `http://localhost:1111` (or `http://127.0.0.1:1111`). Zola watches the files for changes and rebuilds the site automatically, so you can leave the tab open while making changes to the site, and a couple seconds after making a change, you'll see the website refresh and your changes will be visible.

Most of the written content of the site is stored in Markdown files (`.md` files) that can be found in the `content/` directory. Markdown syntax is considered by most to be pretty easy to pick up even if you don't know it, so even those unfamiliar with programming should have no trouble getting the hang of it and making content changes with a little bit of tinkering.

If you want to make more structural changes to the site, such as to the layout, styling, behavior, etc., you'll have to dive into the more technical side of the site (HTML, CSS, Tera templates, etc.). An explanation of those is beyond the scope of this README, but the files you'll most likely want to change are `sass/main.scss`, which controls all of the visual styling of the site, and the `.html` files in the `templates/` directory, which determine the structural layout of the pages throughout the site.

## AI Usage Disclosure

This website was made with the assistance of artificial intelligence (AI), namely Anthropic's [Claude](https://claude.com/). AI was used in creating the layout, styling, and functionality of this website, but did not generate any of the written content. All of that, including this README, was written by [me](https://github.com/chris-t-jansen).

I am hoping, at some point, to find a reasonable way to include the AI chat logs involved in the creation of this site, but so far haven't found a good way to achieve that. If I do, I'll update this section to include links to those.

## Licenses

### Root

The Root board game is designed by [Cole Wehrle](https://buriedgiant.com/), with art by [Kyle Ferrin](https://kyleferrin.bigcartel.com/), and published by [Leder Games](https://ledergames.com). All faction names, artwork, and game content are the property of Leder Games. This website is an unofficial fan site, and is not affiliated with or endorsed by Leder Games.

### Fonts

The fonts used throughout this website are used under the terms of the [SIL Open Font License Version 1.1 (OPL-1.1)](https://openfontlicense.org/open-font-license-official-text/). The following fonts are used in the site:

- [Uncial Antiqua](https://fonts.google.com/specimen/Uncial+Antiqua) by Astigmatic, via Google Fonts
- [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) by Claus Eggers Sørensen, via Google Fonts
- [Libre Baskerville](https://fonts.google.com/specimen/Libre+Baskerville) by Impallari Type, via Google Fonts

### Source Code

The source code for this website, insofar as it is mine to license, is licensed under the **MIT License** ([LICENSE-MIT](LICENSE-MIT) or <https://opensource.org/license/MIT>). Unless you explicitly state otherwise, any contribution intentionally submitted by you for inclusion in this project shall be licensed under the terms of the MIT License, without any additional terms or conditions.
