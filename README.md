# okada-project-docs

## ローカルでのプレビュー

VSCode で DevContainer を起動

```shell
hugo mod tidy
hugo server --logLevel debug --disableFastRender -p 1313
```

## テーマの更新

```shell
hugo mod get -u
hugo mod tidy
```

[Update modules](https://gohugo.io/hugo-modules/use-modules/#update-modules)

