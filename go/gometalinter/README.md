# gometalinter.json

## Usage

```sh
$ gometalinter --config gometalinter.json
```

## Linters section

`gas` configuration is overridden to disable some rules.

Disabled rules

- G103
- G104
- G201
- G202
- G204
- G301
- G302


## Disable section

Some linters are noisy, has false positive or unnecessary. So, the linters are disabled.

## Cyclo section

The configuration is same as `--cyclo-over` option.
It is used by gocyclo
