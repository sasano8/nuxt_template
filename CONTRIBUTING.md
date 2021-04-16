
# Install
次のコマンドでアプリケーションに必要なモジュールをインストールする。

``` shell
yarn install
```

# フォーマッタ動作確認
`sample.ts`などを作成し、次のコードをエディタで保存すると自動フォーマットされる。

```
function test(){
    console.log("test");;;;;;;
        console.log("test");;;;;;;
}
```

# Debug
次のコマンドでデバッグアプリケーションを起動する。

```
yarn dev
```

# 開発時の注意

## scriptタグをtypescriptだと認識させる。
```typescript
<script lang="ts"></script>
```

# memo

```bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate
```