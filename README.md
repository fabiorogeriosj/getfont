# GetFont

[![GetFont Logo](src/getfont.png)](https://www.npmjs.com/package/getfont)

A simple download font for use in webapp.
https://www.npmjs.com/package/getfont



## Install


```
$ npm install -g getfont
```

## Get a font

> In version 1 just work Google Fonts

###You can get by name:

```
$ getfont Ubuntu
```

More size and family

```
$ getfont "Ubuntu:400,300,700|Open+Sans:400,300"
```

###You can get by URL:

```
$ getfont "https://fonts.googleapis.com/css?family=Ubuntu"
```

###You can get by code generated in host:

```
$ getfont "<link href='https://fonts.googleapis.com/css?family=Ubuntu' rel='stylesheet' type='text/css'>"
```

###You can force download format font:

> By default the download is .woff2

```
$ getfont "Ubuntu:400,300,700|Open+Sans:400,300" --woff
```

Formats:
```
--ttf: Get font format .ttf
--woff: Get font format .woff
--woff2: Get font format .woff2
--eot: Get font format .eot
```

###Project Ionic:

You can add the source using the parameter ```--ionic```

```
$ getfont Ubuntu --ionic
```

## Licence
[MIT License](./LICENSE)
