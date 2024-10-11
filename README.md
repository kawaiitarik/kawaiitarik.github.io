# bikepacking

## Adding images

I use 1024x768px as image size, so usually they need to be scaled down.
This can easily be done with:

``` shell
magick mogrify -resize 1024x768  *.jpg
```

## Run locally

To run it locally you need `ruby` and the gem `bundle` (`gem install bundle`).

Then you can run `bundle install` to install the dependencies.

After that you can finally run `bundle exec jekyll serve` to run it locally!
