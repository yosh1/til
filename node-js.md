# Node.js

## REPL

REPL (レプル) とは、 Read-eval-print loop の略称で、入力したコードをその場で実行して、結果を表示するツール。
対話型？

```
$ node

> 2 * 3
> 6
```

## Strictモード

JavaScriptをStrictモードで起動するときは、ファイルの最初に以下を追加する。

```
'use strict';
```

ただし、Node.js ではモジュールという仕組みを使っているため、無名関数で囲う必要はない。
