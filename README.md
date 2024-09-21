<!-- BEGIN BADGES -->
[![Netlify Status](https://api.netlify.com/api/v1/badges/6014bb7d-6295-4d06-9de3-45cbd9592e64/deploy-status)](https://app.netlify.com/sites/vincenzocoia/deploys)
<!-- END BADGES -->

# My Website

This website uses Hugo Blox to generate a static website, which is hosted on Netlify. It uses two themes, Academic CV and Landing Page, so that it can incorporate a larger collection of blocks.

## Structure

Main "landing pages" (all on the menu)

- Main, `content/_index.md`: overview of Vincenzo
- Probaverse, `content/probaverse/_index.md`: overview of the probaverse, intended for those who want to learn more about the probaverse (like tidyverse.org)
- About, `content/about/_index.md`: showcase of skills for those who may want to work with me.
- Posts, `content/posts/`: not quite a landing page (yet?), but is my "outreach" homepage for blog posts, tutorials, courses, videos, etc. Doesn't need an `_index.md` because Hugo Blox just "knows" how to format this page somehow.

### Generating Publications

My website lists my publications. These are generated from bibtex. There are two files, under `content/`:

- `pubs-featured.bib`: featured publications for my main landing page.
- `pubs-not_feat.bib`: all other publications.

Move publications between these two files. 

I use [academic-file-converter](https://github.com/GetRD/academic-file-converter) to convert each bibtex entry to `content/publication/ENTRY` (as recommended by Hugo Blox):

1. Navigate to `content/` in terminal.
2. Execute the following commands:

```
academic import pubs-featured.bib publication/ --featured
academic import pubs-not_feat.bib publication/
```

3. Edit the `index.md` markdown, especially removing that final line of canned markdown that only appears for featured publications.

Notes: 

- The `--overwrite` tag will overwrite existing output folders. But this workflow was never intended to be fully reproducible, because of the manual edits that are sometimes required in the index files.

## Hugo Blox Links

Documentation: https://docs.hugoblox.com/

Themes on github:

- Landing page theme: 
	- GitHub: https://github.com/HugoBlox/theme-landing-page
	- Demo page: https://theme-landing-page.netlify.app/
- Academic CV theme: 
	- GitHub: https://github.com/HugoBlox/theme-academic-cv
	- Demo page: https://academic-demo.netlify.app/

List of all templates: https://hugoblox.com/templates/ 