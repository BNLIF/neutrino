This is the repo for the [BNL Neutrino homepage](https://bnlif.github.io/neutrino/). Anyone in the [BNLIF](https://github.com/BNLIF) organization can edit the repo. To become a member, contact any [existing owners](https://github.com/orgs/BNLIF/people?query=role%3Aowner).

## Edit the pages

The repo uses [GitHub Pages](https://pages.github.com/) to automatically publish the website after each commit. Currently, the following pages that can be edited:
 * [index.md](index.md)
 * [sidebar and layout](_layouts/default.html)

The pages use the [Markdown](https://www.markdownguide.org/basic-syntax/) syntax to avoid writing html directly. You can edit the files directly in the web browser (click the pencil icon that says "Edit this file" on individual file's page). After each commit, GitHub Pages will rebuild the website and the new content will be available within a minute or two.


## Preview the website locally

The cautious ones may want to preview the website before committing the changes. This involves a few more steps to set up the development environment locally. 
1. Clone the repo to your local directory 
2. Install [Ruby](https://www.ruby-lang.org/en/documentation/installation/) if it's not already installed.
3. Install [bundler](https://bundler.io/)
4. Install [Jenkyll](https://jekyllrb.com/docs/installation/)
5. Run `bundle install` under the local repo's directory.
6. Run `bundle exec jekyll serve` and go to `http://localhost:4000/edg/` to preview the website. 
7. Make some changes, preview the website, and commit the changes if everything looks as desired.
