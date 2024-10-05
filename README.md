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

## インストール方法

このプロジェクトを使用するには、以下の手順に従ってください。

```bash
# リポジトリをクローンします：
git clone https://github.com/seiichikick0404/RestaurantChainMockup.git
```

```bash
# プロジェクトディレクトリに移動します：
cd RestaurantChainMockup
```

```bash
# 必要な依存関係をインストールします（`composer` が必要です）：
composer install
```

```bash
# ローカルサーバーの起動(ポート番号はご自由に)
php -S localhost:8000
```

## 使用方法

### 入力フォームに値を入れる

以下のフォームを埋めて送信を押すと選択したファイルタイプが出力する

- 従業員数
- 給与範囲
- ロケーション数(店舗)
- 郵便番号 最小値
- 郵便番号　最大値
- ファイルタイプ(HTML, JSON, TXT, Markdown)

<img width="1392" alt="スクリーンショット 2023-11-17 22 05 10" src="https://github.com/seiichikick0404/RestaurantChainMockup/assets/69625901/b920e9f5-1c4b-4930-b734-fce65e8962f9">

### HTML を選択した場合

<img width="1536" alt="スクリーンショット 2023-11-16 23 10 42" src="https://github.com/seiichikick0404/RestaurantChainMockup/assets/69625901/0d62bcd2-9d5b-4677-a1fb-00d72a86a4cb">

### JSON を選択した場合

json 形式でファイルがダウンロードされます。
<img width="724" alt="スクリーンショット 2023-11-17 22 08 47" src="https://github.com/seiichikick0404/RestaurantChainMockup/assets/69625901/4e5b6611-4aa9-4e5c-ae6e-f54e53b8cbb6">

### TXT を選択した場合

テキスト形式でファイルがダウンロードされます。
<img width="683" alt="スクリーンショット 2023-11-17 22 10 36" src="https://github.com/seiichikick0404/RestaurantChainMockup/assets/69625901/957209d9-8a25-40f2-82ca-98cb0fae3ca4">

### マークダウンを選択した場合

マークダウン形式のファイルがダウンロードされます。
<img width="1174" alt="スクリーンショット 2023-11-17 22 11 55" src="https://github.com/seiichikick0404/RestaurantChainMockup/assets/69625901/53f13d78-a04b-4df0-8111-ce9f52ea1f85">
