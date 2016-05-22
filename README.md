素振り用

## セットアップ

```bash
git clone git@github.com:vwxyz/sandbox-elm.git
nvm i v6.2.0
npm i -g elm
npm i
```
## Elmのversion

最新版の`0.17.0`
`0.16.0`を動かすこともできる

```bash
elm  # --> Elm Platform 0.17.0 - a way to run all Elm tools...
npm run elm # --> Elm Platform 0.16.0 - a way to run all Elm tools...
```


### `node-version`

```
v6.2.0
```

### `.envrc`

```bash
# gitのusername/emailを切り替える
git config user.name vwxyz
git config user.email feeddict@gmail.com
git config --list --local
```

`direnv allow .`
