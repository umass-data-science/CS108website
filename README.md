# About
This repository stores the course website for CS190f/CS108: Foundations of Data Science at UMass Amherst.

This is a [Jekyll](https://jekyllrb.com/) website hosted on [GitHub Pages](https://pages.github.com/), which means the website can be updated easily by simply editing the Markdown files.

# Deploy the site with GitHub Pages
GitHub will automatically deploy the website to <https://umass-data-science.github.io/190fwebsite> when you push the configured branch, check on your GitHub repository > Settings > Pages.

GitHub has [comprehensive documentation for deploying Jekyll sites on GitHub Pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll).

# Testing the site locally
You can test the website on your own computer before deploying to GitHub Pages.

Follow the [Jekyll Installation instructions](https://jekyllrb.com/docs/installation/) to install [Ruby](https://www.ruby-lang.org/en/) and [Ruby Gems](https://rubygems.org/pages/download). You'll also install Jekyll and [Bundler](https://bundler.io/) by running `gem install jekyll bundler`. Finally, follow the [instructions provided by GitHub](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll) to build and test your Jekyll site locally.

The basic commands are:
- `bundle install` to build your site and install all Gem dependencies
- `bundle exec jekyll serve` to run your site locally at the server address printed out by this command