# NSL Website

This is the website of the Networked Systems Laboratory (NSL) at the University of Southern California.

We thank [Allan lab](http://www.allanlab.org/aboutwebsite.html) for the template.

## Installation

- Install Jekyll: [Jekyll for Ubuntu, MacOS, Windows](https://jekyllrb.com/docs/installation/)
- `bundler install`
- `bundler exec jekyll build` - Website will be built
- `bundler exec jekyll serve` - Website will be served on localhost:4000

## Steps to update the website

- `git clone https://github.com/USC-NSL/USC-NSL.github.io.git`
- `cd USC-NSL.github.io`
- `git checkout -b main` -> Branch containing the website source code.
- Make changes only to the main branch and commit. An automated worflow deploys the website from main branch to the gh-pages branch.

## A note on bibliography entries

Our website uses jekyll/scholar. To have a publication show up on our pubs page, all you need to do is to add your bib entry to `_bibliography/papers.bib`. Then, when you push your changed, github will automatically populate the pubs page.

When you add a bib entry, the following fields have special meaning:

- `abbr` adds a badge to the publication. For example, `abbr = {NSDI}` will add an NSDI badge to the pub.
- `code` is a link to a github repository containing code released associated with the paper. If this entry is present, then a "code" button appears under the paper's entry.
- `slides` is similar to `code`.
- setting `bibtex_show` to 1 will add a `bib` button, which, when clicked, will reveal the bib entry.

You can add other entries by configuring `_layouts/bib.html`.

## Add/Update personal page

