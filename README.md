# TextLint
a linter for "normal" documents (eg. mails, dissertations, doctoral theses, ...)

## Status

just started

## How to

when it's finished, it will be used like this:

```sh
cat README.md | pandoc -f markdown -t plain | textlint
```

or

```sh
cat Thesis.tex | pandoc -f latex -t plain | textlint
```

## License

MIT
