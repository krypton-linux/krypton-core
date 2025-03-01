# krypton-core

Krypton Linuxのpacmanパッケージリポジトリ。

# 利用可能なサーバー

メインサーバー(推奨)

```pacman.conf
[krypton-core]
Server=https://krypton-linux.com/krypton-core/repo
SigLevel=Never
```

CDN(メインサーバーが重い場合、使用を推奨)

```pacman.conf
[krypton-core]
Server=https://rawcdn.githack.com/krypton-linux/krypton-core/main/repo
SigLevel=Never
```
