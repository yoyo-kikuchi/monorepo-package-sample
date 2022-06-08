# monorepo-package-sample

GitHub packages モノリポ構成 package 検証サンプル

## usage

各 Package に設置してある`.npmrc.example`を`.npmrc`にリネームし PERSONA_ACCESS_TOKEN と GitHub ユーザー名を設定する。

### Publish コマンド

- npm

```sh
npm publish --no-workspaces
```

- yarn

```sh
yarn publish
```
