## Start jekyll 

To start the jekyll service and serve the site on http://localhost:4500/ run:
  bundle exec jekyll serve --port 4500

When you changed something in _config.yml run

  bundle exec jekyll serve --port 4500

again.


## Tools

## How to convert all png screenshots to jpg files

    mogrify -format jpg -resize 840 *.*