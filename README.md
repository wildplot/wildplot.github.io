# Wildrate Website
The website - published to [wildrate.org](www.wildrate.org).

Built on standard Jekyll support for github pages - the default document source is the `gh-pages` branch.

## To test it all locally...

* Install Jekyll https://jekyllrb.com/docs/installation/
* Check you also have the Ruby Bundler tool (if not `gem install bundler`)
* Clone this repo and go checkout the branch `gh-pages`
* Run `bundle install`
* Run `bundle exec jekyll serve`
* Point the browser at [http://localhost:4000](http://localhost:4000)

## Then when happy, publish...

* Make sure (under Settings) this repo is public and has Github pages enabled
* Simply commit and push the `gh-pages` branch
* The domain is hooked up via [this information](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/about-custom-domains-and-github-pages#using-an-apex-domain-for-your-github-pages-site)
