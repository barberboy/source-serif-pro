# Source Serif Pro

Source Serif Pro is a set of OpenType fonts to complement the [Source Sans Pro](https://github.com/adobe-fonts/source-sans-pro) family.
In addition to a functional OpenType font, this open source project provides all of the source files that were used to build this OpenType font by using the AFDKO makeotf tool.

## Web font installation instructions

### Clone with git

```sh
cd styles/fonts
git clone https://github.com/barberboy/source-serif-pro
```

```html
<link rel="stylesheet" href="/styles/fonts/source-serif-pro/source-serif-pro.css">
```


### Download

Download and unpack the [.zip archive](https://github.com/barberboy/source-serif-pro/archive/master.zip):

```sh
cd styles/fonts
wget https://github.com/barberboy/source-serif-pro/archive/master.zip
unzip master.zip
mv source-serif-pro-master source-serif-pro
rm master.zip
```

```html
<link rel="stylesheet" href="/styles/fonts/source-serif-pro/source-serif-pro.css">
```


### Bower

```sh
bower install barberboy/source-serif-pro
```

```html
<link rel="stylesheet" href="/bower_components/source-serif-pro/source-serif-pro.css">
```

If you’d like bower to put it in a different directory, just create a
[`.bowerrc`](http://bower.io/docs/config/) file and specify the
[`directory`](http://bower.io/docs/config/#directory) location:

```json
{
  "directory": "app/public",
  "analytics": false
}
```

### CDN

Quickly test Source Code Pro on your site by using the CDN hosted by [RawGit].
Feel free to use it in production as well:

```html
<link rel="stylesheet" href="https://cdn.rawgit.com/barberboy/source-serif-pro/1.017/source-serif-pro.css">
```
[RawGit]: https://rawgit.com/

## Getting Involved

Send suggestions for changes to the Source Serif OpenType font project maintainer, [Frank Grießhammer](mailto:opensourcefonts@adobe.com?subject=[GitHub] Source Serif Pro), for consideration.

## Further information

For information about the design and background of Source Serif, please refer to the [official font readme file](http://htmlpreview.github.io/?https://github.com/adobe-fonts/source-serif-pro/blob/master/SourceSerifProReadMe.html).
