# @ichiql/numberize

```shell
pnpm add @ichiql/numberize
```

```shell
npm install @ichiql/numberize
```

```shell
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
