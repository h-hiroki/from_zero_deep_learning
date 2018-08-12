# なにこれ
ゼロから作るDeep Learningの勉強用リポジトリ

# dockerの使い方

1. dokcerコンテナ起動
``` docker-compose up ```

2. 起動ログ確認
以下のようなログが出力されるので3行目のURLをコピーする
```
anaconda_1  |     Copy/paste this URL into your browser when you connect for the first time,
anaconda_1  |     to login with a token:
anaconda_1  |         http://e5e87ff4df33:8888/?token=b83cee3943832007245096500679352200bce65fd25f52b9&token=b83cee3943832007245096500679352200bce65fd25f52b9
```

3. URLのホストは0.0.0.0に変更する
```
http://0.0.0.0:8888/?token=b83cee3943832007245096500679352200bce65fd25f52b9&token=b83cee3943832007245096500679352200bce65fd25f52b9
```

4. ブラウザにURLを貼り付けて完了

# 補足情報
スクリプトたちはworkspace配下に格納されるよ
