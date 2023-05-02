# Wildrate Website

The website - published to [wildrate.org](www.wildrate.org).

Built on standard Jekyll support for github pages - the default document source is then the `gh-pages` branch.

See here for [full documentation](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll)

## To build/test it all locally...

* Install `ruby`
* Check you also have the Ruby Bundler tool (if not `gem install bundler`)
* (If have both installed - you should be able to do `which ruby` and `which bundle`)
* First time only! run `bundle install`
* After that you might also need to run `bundle update` to resolve more recent dependencies
* (You might also have to do this as `sudo` or admin if system wide)
* Modify the content, _config.yaml etc to change global site appearance etc.
* NOTE: the cayman theme is installed as per https://github.com/pages-themes/cayman
* *** To then test locally, run `bundle exec jekyll serve` ***
* Then point the browser at [http://localhost:4000](http://localhost:4000)
* Notice that `jekyll serve` will watch this directory and automatically update as you make changes!

## Then when happy, publish...

* Make sure (under Settings) this repo is public and has Github pages enabled
* Simply commit and push your changes as a PR to the `gh-pages` branch
* Once that goes through, the site should be published and live
* The domain is hooked up via [this information](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/about-custom-domains-and-github-pages#using-an-apex-domain-for-your-github-pages-site)
