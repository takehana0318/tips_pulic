# Tips of Tmux

## settings
[OSのクリップボードと同期](https://maku.blog/p/tb6s2ck/)
[tmuxでコピペ](https://qiita.com/chatrate/items/394122d3225ab42ca6f1)

## session
| コマンド | 内容 |
|---|---|
| tmux new -s NAME | セッションを作成 |
| tmux a -t NAME | 既存のセッションに接続 |
| tmux kill-session -t NAME | セッションの削除 |
| Ctrl+b then d | セッションのデタッチ |
|  Ctrl+b then $ | セッション名の変更 |


## window
| コマンド | 内容 |
|---|---|
| Crtl+b then c | ウィンドウの作成 |
| Ctrl+b then , | ウィンドウ名の変更 |
| Ctrl+b then & | ウィンドウの削除 |
| Ctrl+b then w | ウィンドウの表示 |
| Ctrl+b then p | 次のウィンドウへ移動 |
  
## pane
| コマンド | 内容 |
|---|---|
| Ctrl+b then " | ペインの水平分割 |
| Ctrl+b then % | ペインの垂直分割 |
| Ctrl+b then o | ペイン間の移動 |
| Ctrl-b :resize-pane -D 10	| 下部ペインのサイズ変更 |

## others
| コマンド | 内容 |
|---|---|
| Ctrl+b then [ | スクロール |
