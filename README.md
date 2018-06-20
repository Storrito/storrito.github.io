## Start jekyll 

To start the jekyll service and serve the site on http://127.0.0.1:4000/ run:
  bundle exec jekyll serve

When you changed something in _config.yml run

  bundle exec jekyll serve

again.


## Tools

## How to convert all png screenshots to jpg files

    mogrify -format jpg -resize 840 *.*