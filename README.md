# bikepacking

## Adding images

I use 1024x768px as image size, so usually they need to be scaled down.
This can easily be done with:

``` shell
magick mogrify -resize 1024x768  *.jpg
```
