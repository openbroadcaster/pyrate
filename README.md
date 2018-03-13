#openbroadcaster.com

[![GitHub license](https://img.shields.io/github/license/openbroadcaster/openbroadcaster.github.io.svg?style=flat-square)](https://github.com/openbroadcaster/openbroadcaster.github.io/blob/master/LICENSE)
<img src="img/FOC.png" alt="OpenBroadcaster" width="280" align="right">

This repository holds the source code to the [OpenBroadcaster PyrateRadio](http://support.openbroadcaster.com/PyrateRadio/) website, a [Jekyll](http://jekyllrb.com/)-powered site hosted for free on [GitHub Pages](https://pages.github.com/).

### Development Notes

#### Setting up a local instance
The project requires Ruby2.0, and nodejs. If no ruby environment is installed, setup as follows:

1. `apt-get install ruby2.0 ruby2.0-dev gem bundler zlib1g-dev nodejs`
2. Relink the /usr/bin/ruby and /usr/bin/gem executables to the 2.0 versions:
3. `gem install RedCloth -v '4.2.9'`
4. `gem install nokogiri -v '1.6.6.2'`


After cloning this repository, run:

1. `bundle install` to download dependencies required to build.
2. `bundle exec jekyll serve` to run locally or `bundle exec jekyll build` to generate into `./site` directory.

### Screenshot


<img src="https://cdn.rawgit.com/jekyll/brand/master/jekyll-logo-light-transparent.png" alt="Made with Jekyll" width="140" align="right" /> <img src="http://bower.io/img/bower-logo.svg" alt="Made with Bower" height="70" align="right">
