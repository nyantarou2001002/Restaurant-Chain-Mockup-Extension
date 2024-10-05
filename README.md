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

- レストランチェーンの情報管理
- レストランロケーションの管理
- 従業員情報の管理
- 情報の HTML での出力、Markdown、 JSON、テキスト形式でのエクスポート

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

<img width="1392" alt="スクリーンショット 2023-11-17 22 05 10" src="https://github.com/seiichikick0404/RestaurantChainMockup/assets/69625901/b920e9f5-1c4b-4930-b734-fce65e8962f9">

