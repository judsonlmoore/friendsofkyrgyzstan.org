# Friends of Kyrgyzstan - Admin notes

Welcome to the exciting world of Jekyll! It's not as visual as WordPress but it's a whole lot faster and fancier. Here are some notes to refer to as you go down this journey.

## Common commands

To rebuild the site `jekyll build`

To serve the site locally `bundle exec jekyll serve`

To clean the cache `jekyll clean`

To search for errors `jekyl doctor`

## Index new searches

Whenever you publish new content you might need to index it into the search database. To do that, type this in to Terminal: 

`ALGOLIA_API_KEY='5252e71853f05985170b0069e501335e' bundle exec jekyll algolia`

