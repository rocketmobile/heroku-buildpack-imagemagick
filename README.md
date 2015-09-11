heroku-imagemagick-buildpack
=================================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for vendoring the ImageMagick binaries into your project. It doesn't do anything else, so to actually compile your app you should use [heroku-buildpack-multi](https://github.com/ddollar/heroku-buildpack-multi) to combine it with a real buildpack.
