## Start jekyll

To start the jekyll service and serve the site on http://localhost:4500/ run:

    bin/dev

Make sure you have installed Docker on your machine.

Restart the process as soon as you change something in `_config.yml`
file.

## Tools

## How to convert all png screenshots to jpg files

    mogrify -format jpg -resize 840 *.*
