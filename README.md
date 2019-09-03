# leaikkache.github.io

This is the repo for my personnal website

# Setup environment for developpers

## Install tools
We need ruby, and bundle to install jekyll

`apt-get install ruby bundle jekyll`

Take care to install the correct version for ruby : 2.4 at least.

## Install jekyll plugins

When you checkout or pull the code follow these two steps : 
```
bundle install
bundle exec jekyll serve
```

`bundle install`, for now, installs : 
* jekyll-theme-cayman
* jekyll-multiple-languages-plugin 

`bnudle exec jekyll serve` builds and serves the site on http://localhost:4000. It permits to test your developments.
