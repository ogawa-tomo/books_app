# README

## push/pullするためのPAT更新
PATの期限が切れると、pushやpullができなくなる（たぶん）。以下の手順でPATを更新する。

1. GitHubでPAT作成ページにアクセスし、PATを新規作成する。classicのトークンで、repoにチェックすればOK。
  
    https://github.com/settings/tokens

2. 下記コマンドを実行
      ```
      $ git remote set-url origin https://[取得したトークン]@github.com/ogawa-tomo/books_app.git
      ```

参考：https://stackoverflow.com/questions/60757334/git-push-from-visual-studio-code-no-anonymous-write-access-authentication-fai
