![logo.svg](https://cdn.rawgit.com/bubkoo/logo.svg/master/logo.svg)

> Generate svg logo

## Install

```
$ npm install logo.svg -g
```

### CLI

```
$ logo [options]
```

### Options

```
  -l, --logo ??? ............. The logo text. Default is the `name` of the `package.json`.
  -f, --font ??? ............. Specify the font path or url.
  -s, --fontSize ??? ......... Specify the font size. Default `72`.
  -o, --output ??? ........... Specify the output path. Default `logo.svg`
  -c, --config ??? ........... Specify the `.logorc` file.
  -O, --overwrite ............ Overwrite when a logo file exist. Default `true`.
  -k, --kerning .............. Take kerning information into account. Default `true`.
  -d, --divided .............. Generate individual path for every char. Default `false`.
  -V, --version .............. Print the current version.
  -h, --help ................. You're looking at it.
  -h, --help ??? ............. Show details for the specified command.
```

### Examples

```
  $ logo
  $ logo -Odo ./logo/logo.svg
  $ logo --config ./logo/.logorc
  $ logo --help
  $ logo --help font
  $ logo --help config
  $ logo --version
```


### As module

