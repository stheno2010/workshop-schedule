# GitHubの利用方法(for Windows7) #
=================

# 1. Git for Windows をダウンロードする。
    [Welcome to the home page of Git for Windows](http://msysgit.github.io/)

    任意の設定でインストール。

# 2. TortoiseGit をダウンロードする。
    [tortoisegit -Windows Shell Interface to Git-](https://code.google.com/p/tortoisegit/)

    SSHクライアント(TortoisePLink)を選択する。

# 3. 秘密鍵と公開鍵を作成する。
    [puttygen](http://d.hatena.ne.jp/tarurut/20110117/1295285155)
    or
    [ssh-keygen](http://yuheikagaya.hatenablog.jp/entry/2012/12/11/224216)
    で秘密鍵と公開鍵を作成し、以下に保存する。
    C:\Users\[user_name]\.ssh\

# 4. GitHubに公開鍵を登録する。
    SSH Keys > Add SSH key で Key に公開鍵を貼り付ける。
    Titleは任意。

# 5. プロクシを使用する場合はプロクシを設定する。

# 6. GitHubに接続する。

# 以上
