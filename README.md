## stylus-linter - 既存のstylintを少し変更した。

**[変更点]**
- 内部モジュールをアップデート。
- done()メソッドでNode.jsのプログラムが強制終了させられるので、終了させるかどうかのフラグをオプションに追加。

```javascript
stylint(dirPath, config, callbackFn).create({}, {
  processExit: true // trueでprocess.exit()を止める。（デフォルトはfalse）
});
```

## Installation
As part of your project: `npm install stylus-lint (--save, --save-dev)`

As a cli tool: `npm install stylus-lint -g`

## Documents
こちらをご参照ください。

[SimenB/stylint](https://simenb.github.io/stylint/)
