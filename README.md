# vscode extension pack for my personal use

free to grab my code and create your own vscode extension packs

## if you want to create brand new extension pack

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
vsce package
vsce publish
```
