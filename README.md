# Heroku buildpack: Noto Fonts

This is a Heroku buildpack for adding Google's Noto fonts.

### Usage

Create a new Heroku application using this buildpack - 

```
$ heroku create --buildpack https://github.com/emailthis/heroku-buildpack-noto-fonts.git
```

Add this to an existing application - 

```
$ heroku buildpacks:set BUILDPACK_URL="https://github.com/emailthis/heroku-buildpack-noto-fonts.git"
```


---------

Bharani <br>
[EmailThis](https://www.emailthis.me)