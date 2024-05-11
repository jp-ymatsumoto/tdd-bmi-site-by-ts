# テスト駆動開発「身長と体重から BMI を確認するウェブサイト」

## 概要

テスト駆動開発の学習用です。TypeScript と Jest を使用しています。

**問題内容**

身長と体重から BMI を確認するウェブサイトを作成中です。
身長と体重の入力から BMI の出力まで正しく行えるようにテストを実施してください。

**前提条件**

- 入力される値は input 要素の値とします。
- BMI の身長に用いられる数値の有効範囲は 100.0~250.0cm とします。
- BMI の体重に用いられる数値の有効範囲は 15.0~200.0kg とします。
- BMI の値は小数点第１位まで有効とします。
- BMI の値の小数点第２位は切り捨てします。
- 入力される値に間違いがあった場合はアラートをお知らせします。表示内容は開発者が考えてください。
- 最低限、入力値の検証、BMI の計算結果の検証の２種類はテストしてください。関数の粒度は開発者に一任します。

## テスト駆動開発の手順

1. テストケースを作成する

システムの要件を確認し、同値分割法と境界値分析を用いてテストケースを作成してください。
テスト対象は「入力値の検証と BMI」の「計算結果の検証」の２種類です。
例えば、身長と体重の「入力値の検証と BMI」を１つにまとめた場合はテスト対象は１つ、身長と体重の「入力値の検証と BMI」を別々にした場合はテスト対象は２つになります。そのテスト対象の関数内で使用している関数のテスト有無は問いません。

2. ソースファイル(src/bmi.ts)に空の関数を作成する

src/bmi.ts に空の関数を作成してください。

3. テストファイル(src/bmi.test.ts)にテストを実装する

src/bmi.test.ts にテストケースとテストを実装してください。

4. テストを実施する

```bash
npm run test
```

5. ソースファイル(src/bmi.ts)の関数を実装する

すべてのテストケースが通るように、src/bmi.ts の関数を実装してください。

6. テストを実装する

7. すべてのテスト対象が通るまで 2~6 を繰り返す

## ウェブサイトの作成手順

1. ターミナルで開発用サーバを起動する

```bash
npm run start
```

2. ターミナルで TypeScript のファイルの変更を監視する

```bash
npm run watch
```

3. src/main.ts にシステム要件の処理を実装する

index.html、css/style.css、src/main.ts を修正してください。

4. 公開用にビルドする

```bash
npm run build
```

5. ウェブサーバで公開する

ウェブサーバにアップロードするファイルは、index.html、css ディレクトリ、dist ディレクトリなどです。

## 環境構築の手順

1. リポジトリをクローンする

```bash
git clone https://github.com/jp-ymatsumoto/tdd-bmi-site-by-ts.git
```

2. Visual Studio Code で開く

```bash
code tdd-bmi-site-by-ts
```

3. パッケージをインストールする

```bash
npm i
```
