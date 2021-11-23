# Titanicのチュートリアルノートブック

## 更新履歴
- 11/23 : ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]ボタンを追加。その他一部を修正。
- 11/14 : 一部修正。

## 概要
Titanicの簡単な実装が含まれたノートブックです。 

フォルダ構成は以下のようになっています。
- Question : 一部ソースコードが穴埋め状態になったノートブックです。穴を埋めて実装してきましょう。
- Answer : 完全版のノートブックです。Questionの穴埋めを一通り埋めたあと確認用に使いましょう。

また、Questionフォルダには4つのノートブックがあります。
1. LightGBM
2. 全結合ニューラルネットワーク(MLP)
3. TabNet

Answerフォルダには上記3つの解答の他にPyCaretのサンプルコードも収録されています。

基本的に、LightGBM→MLP→TabNetの順番で解いていくことを想定しています。最初は、お手本を見せることを想定しているため、穴埋めする箇所は少ないです。後半になるにつれて穴だらけになっていきます。

## 想定環境

- Google Colaboratory(Googleアカウントが必要です。)

クラウド環境のため、ローカルPCのスペックは特に問いません。

## 使い方

1. ノートブックをGoogle Colaboratoryにコピーする。
   1. 本リポジトリから利用したいノートブックのリンクまで移動する。
   2. 画面上部の![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]ボタンをクリックする。
   3. colab notebookが表示されるので、コピーを自身のマイドライブに保存する。

2. [Kaggleのページ](https://www.kaggle.com/c/titanic)から、Titanicのデータセットをダウンロードし、Google Driveに保存する。
   - Kaggleのアカウントが未登録の場合は、お手数ですが登録をお願いします。
   - ファイル一式は、`/content/drive/MyDrive/Kaggle`直下に配置することを想定していますが、お好みで変更していただいても構いません。




