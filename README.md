<a rel="license" href=""><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a>

# Intro to unix shell

This course is now hosted by [Coding For Reproducible Research (CfRR)](https://coding-for-reproducible-research.github.io/).
This material is still visible at [the deployed site](https://uniexeterrse.github.io/intro-unix-shell/), but any updates and new course dates will be found at [CfRR: Intro to Unix](https://coding-for-reproducible-research.github.io/CfRR_Courses/course_homepages/unix.html).
These notes accompany in-person and online teaching during the two sessions of the Intro to Unix Shell course.

## Source details

This repository is based off of the University of Exeter `UoE-workshop-template` repository.
This template uses Jekyll and GitHub pages to create a workshop guide.

## Ruby and local testing

Jekyll is a ruby Gem. A simple Gemfile has been added.
To test the site locally, clone the repository, and run the following (tested on macOS and Windows).
Ensure `ruby` and `bundler` have been installed, and then run the following from the project root:

```bash
bundle config set --local path 'vendor/bundle'
bundle install
bundle exec jekyll serve
```

Then open the site at the default server address of `http://127.0.0.1:4000`.

## JavaScript and styling

Most of the styling for the site is found in `_sass/jekyll-theme-slate.scss`.
Vanilla JavaScript is used to fold and unfold solution blocks.
These blocks also use two icons from the [fontawesome](fontawesome.com) library.
This open source icon library is far nicer to use than bootstrap.css.
The stylesheet is imported in `_layouts/page.html`.
