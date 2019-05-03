概要
----
ruby、selenium (chrome) をxvfb上で動かすためのDocker環境

背景
----
単純に `headless chrome` を使えばいいじゃないか、と思うかもしれないが目的として `chrome extension` を使いたいというのがまずある。  
残念なことに `headless chrome` 上だと `chrome extension` は使用不可能になる (headありの状態だと自動操縦できる)  
ので `xvfb` 上で `chrome` を起動することで上記の `chrome extension` が起動できない問題を回避している。
