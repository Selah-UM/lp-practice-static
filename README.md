# 概要
レベルアッププログラミングの静的サイト公開の練習リポジトリです。

# プロジェクト管理

このリポジトリのタスクはプロジェクトにてかんりされています。
タスクの追加・進行・完了じは、プロジェクトの更新も忘れないようにしてください。

https://github.com/Selah-UM/lp-practice-static/projects/1

# サイトのURL

https://selah4.s223.xrea.com/

# ssh接続
公開鍵認証でSSH接続できるようになりました。

```
ssh -i ~/.ssh/id_rsa_bitbucket selah4@s223.xrea.com
```

もし家のルータ再起動などでグローバルIPアドレスが変わった場合は、以下のコントロールパネルより、もう一度許可し直してください。
https://cp.xrea.com/site/tools/

# リリース手順

プロジェクトディレクトリで以下のコマンドを実行してください

```
sh deploy.sh
```

# 必要な情報
「XREA.COM NEW SIGNUP」というメールに書かれています。
フラグ付きにしてあります。
