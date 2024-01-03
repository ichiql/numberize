# Deprecated

このパッケージは非推奨となりました
今後は [anoare](https://github.com/ichiql/anoare) をご使用ください :)

This package has been deprecated.
Use https://github.com/ichiql/anoare instead.

---

# @ichiql/numberize

```shell
pnpm add @ichiql/numberize
npm install @ichiql/numberize
yarn add @ichiql/numberize
```

string や bitint などを number に変換する。

Convert string, bitint, etc... to number.

```js
import numberize from '@ichiql/numberize'

numberize('123') // 123
numberize(BigInt(123)) // 123
numberize('$1,000') // 1000
numberize('invalid value') // NaN
```
