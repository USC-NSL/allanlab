# NSL Website

This is the website of the Networked Systems Laboratory (NSL) at the University of Southern California.

We thank [Allan lab](http://www.allanlab.org/aboutwebsite.html) for the template.

## Steps to update the website

Setup:

- `git clone https://github.com/USC-NSL/USC-NSL.github.io.git`
- `cd USC-NSL.github.io`
- `git checkout -b main` -> Branch containing the website source code.
- Copy `USC-NSL.github.io` folder in your local machine to another folder say, `USC-NSL.github.io_gh_pages`
- `cd USC-NSL.github.io_gh_pages`
- `git checkout -b gh-pages` -> Branch containing HTMLs generated from jekyll build.

Update:

- `cd USC-NSL.github.io` -> Points to the main branch
- Commit changes to the website repository in the main branch
- Run `bundle exec jekyll build` under `USC-NSL.github.io` folder
- Copy the contents inside `_site` folder to `USC-NSL.github.io_gh_pages`
- `cd USC-NSL.github.io_gh_pages` and commit the changes to gh-pages branch.

To Do:

- Use Github Action Bot to automate the above steps so that gh-pages branch is automatically updated when the main branch is updated. Ref: [ai-folio](https://github.com/alshedivat/al-folio)
