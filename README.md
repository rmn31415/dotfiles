# dotfiles
dotfiles です。ホームディレクトリに入れるなりしてご利用ください.

## Vimに関する諸注意
Vim の設定ファイル `.vimrc`に関する諸注意です。
### バックアップディレクトリに関する注意
このリポジトリの`.vimrc`は、ホームディレクトリ下に`.vim-backup-undo`ディレクトリが、 さらにその下に`backup` ディレクトリおよび `undo` ディレクトリがあることを前提としています。それぞれの位置にバックファイルとUNDOファイルが作成されます。このディレクトリがなかったり、パーミッションがなかったりするとファイル保存時にエラーになりますのでご注意ください。

### .vimrc の NeoBundle に関する注意
このリポジトリの`.vimrc`は、[NeoBundle](https://github.com/Shougo/neobundle.vim) がインストールされていることを前提としています。まだ入れていない場合は入れてからホームディレクトリに配置するなどしてください。

## ライセンス
Public Domain (Unlicensed)