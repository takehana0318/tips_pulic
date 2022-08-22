# Tips of vim editor

## 移動
|コマンド  |内容  |
|---|---|
| :edit FILE_NAME | open file |
|h,j,k,l  |上下左右に移動  |
| c-w + hjkl | 分割画面の移動 |
|w | 単語の先頭に進む |
|b | 単語の先頭に戻る |
| 0	| 行頭 |
| ＾ | インデント頭 |
| $ | 行末 |
|ctrl + u | 半画面分 上へ |
|ctrl + d | 半画面分 下へ |
|gg | ファイルの先頭 |
|G | ファイルの末尾 |

## コピペ・削除・検索・置き換え
|コマンド  |内容  |
|---|---|
| v + 移動 then p | 範囲を指定してコピー |
| yy | 1行コピー |
| p | 改行してペースト |
| :set paste! | インデント無でペースト |
| dw | 一単語削除 |
| :%d | 全削除 |
| /WORD | 検索 |
| :%s/from/to/gc | 全行置き換え |
| shift + v then shift + > | 一括インデント | 
| Ctrl+v then Shift+i | insert multiply line |

## nerdtree
|コマンド  |内容  |
|---|---|
| s | 垂直に分割で開く |
| c-w hjkl | 他の画面に移動 |
| m then a | ファイルを作成 |
| :e! | ファイル再読み込み |
| r | ファイルツリーの更新 |
| t | 新しいタブで開く |
| gt | 次のタブに移動 |


## 設定
```
vundle
https://qiita.com/nordliches-klang/items/caf939e3ef561a4491e8
vim +PluginInstall +qall

ファイルツリー
https://qiita.com/zwirky/items/0209579a635b4f9c95ee
```
