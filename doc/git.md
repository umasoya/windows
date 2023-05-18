Windows内からgitコマンドを実行する場合､下記のように `-c` で鍵を指定してやる｡


```sh
git -c core.sshCommand="ssh -i C:/Users/umasoya/crypto/github/id_ed25519 -F /dev/null" clone ...
```