# vscode extension pack for my personal use

Free to grab my code and create your own vscode extension packs.

## if you want to create brand new extension pack from scratch(not recommended)

```shell
npm install -g yo generator-code
yo code
```

## publish requirements

```shell
npm install -g vsce
```

## publish

```shell
vsce login your-vscode-marketplace-id

cd some-random-pack
vsce package
vsce publish
```
