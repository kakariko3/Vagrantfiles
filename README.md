# Vagrantfiles

## Vagrantコマンド

```
# 仮想マシンの起動
vagrant up

# 仮想マシンの停止
vagrant halt

# 仮想マシンの再起動(停止 & 起動)
vagrant reload

# 仮想マシンの状態を一覧表示
vagrant global-status

# 仮想マシンのポートフォワード設定を確認
vagrant port

# 仮想マシンを削除
vagrant destroy

# 仮想マシンにssh接続
vagrant ssh

# 仮想マシンにssh接続(sshコマンド)
ssh vagrant@localhost -p 2222

# 仮想マシンのssh接続情報を表示
vagrant ssh-config
```

## 参考資料

### Vagrantコマンド
https://qiita.com/oreo3@github/items/4054a4120ccc249676d9<br>
https://qiita.com/0ta2/items/69c2378600bf8adaac5c<br>
https://kekaku.addisteria.com/wp/20190123181923

### Vagrant + Docker + VSCode
https://qiita.com/anfangd/items/63ab95a2005cb2d1f196<br>
https://gendosu.jp/archives/3439

### Ubuntu Docker環境構築
https://qiita.com/tkyonezu/items/0f6da57eb2d823d2611d<br>
https://zenn.dev/k_neko3/articles/76340d2db1f43d<br>
https://zenn.dev/ciffelia/articles/dc2f8acb33ace6
