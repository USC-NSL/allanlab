# NSL Website

This is the website of the Networked Systems Laboratory (NSL) at the University of Southern California.

We thank [Allan lab](http://www.allanlab.org/aboutwebsite.html) for the template.

## Steps to update the website

Setup:

- `git clone https://github.com/USC-NSL/USC-NSL.github.io.git`
- `cd USC-NSL.github.io`
- `git checkout -b main` -> Branch containing the website source code.
- Make changes only to the main branch and commit. An automated worflow deploys the website from main branch to the gh-pages branch.

## A note on bibliography entries

When you add a bib entry, the following fields have special meaning:

- `abbr` adds a badge to the publication. For example, `abbr = {NSDI}` will add an NSDI badge to the pub.
- `code` is a link to a github repository containing code released associated with the paper. If this entry is present, then a "code" button appears under the paper's entry.
- `slides` is similar to `code`.
- setting `bibtex_show` to 1 will add a `bib` button, which, when clicked, will reveal the bib entry.

You can add other entries by configuring `_layouts/bib.html`.
