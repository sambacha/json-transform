# stdin2json

> Command-line tool for converting **anything** to JSON.

## Features

- Eat everything, spits out json
- Supports **json**, **yaml**, **toml**, **xml**, **ini**, **cli tables**
- Formatting and highlighting
- Standalone binary

## Install

```
$ npm install -g stdin2json
```


## Usage

```
$ stdin2json resp.xml > resp.json

$ cat config.yaml | stdin2json > config.json

$ stdin2json deps.toml

$ ps | eat | fx .PID
```

### Other examples

Use it with [fx](https://github.com/antonmedv/fx) tool for extracting needed fields.

```
$ cat response.xml | eat | fx .Document.Title
```

## Related

- [fx](https://github.com/antonmedv/fx) – cli JSON processor on JS
- [any-json](https://github.com/any-json/any-json) - alternative cli tool for converting formats

## License

MIT
