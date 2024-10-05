# RestaurantChainMockup

## 概要

Restraurant Chain Mockup を拡張して、ユーザーがフォームに入力できるようにしました。レストランチェーンに対して、ユーザーがさまざまなオプションを選択できるようにします。
- チェーンが持つ従業員の数を選択
- 従業員の給与範囲を選択
- 場所の数を入力
- 場所の郵便番号の範囲を設定
- 生成したいファイルのタイプを選択: HTML、JSON、TXT、または MarkDown。
この拡張により、ユーザーは自分の要件に応じてレストランチェーンのデータをカスタマイズして生成することができるようになりました。

## 機能

入力フォームページ
![スクリーンショット 2024-10-05 14 46 51](https://github.com/user-attachments/assets/1fb15020-2f8e-425d-a1a6-f43bb8a25c93)

モックアップページ(HTMLを選択した場合)
![スクリーンショット 2024-10-05 14 47 15](https://github.com/user-attachments/assets/26eab1a3-718a-4f19-a8a7-93171b9900d2)


## 使用方法


1.このリポジトリをクローンして開いてください。

2.下記のコマンドを実行してComposerがインストールされているか確認してください。
インストールされている場合は４にされていない場合は３に進んでください。
```
composer -v
```

3.下記のコマンドを実行してCompossorをインストールください。
```
curl -sS https://getcomposer.org/installer | php
```
```
sudo mv composer.phar /usr/local/bin/composer
```
上記の2つのコマンドを実行したら下記のコマンドでインストールされているのか確認してください。
```
composer -v
```

4.下記のコマンドを実行してローカルサーバーを起動してください
```
php -S localhost:8080
```

5.以下のフォームを埋めてGenerateボタンを押すと選択したファイルタイプが出力されます

- number of Enployees
- salary
- number of Locations
- Minimum postal code
- Max postal code
- Download Format(HTML, JSON, TXT, Markdown)

