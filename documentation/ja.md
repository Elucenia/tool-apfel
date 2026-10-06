<!-- ELUCENIA technical documentation · apfel · ja · no clinical/professional/rights approval -->

# Apfelスコア（術後悪心・嘔吐）

[条件・出典・許諾](https://elucenia.org/ja/tools/apfel)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 女性

`fem`

### 非喫煙者

`naofuma`

### 術後悪心・嘔吐または乗り物酔いの既往

`historia`

### 術後オピオイド使用予定

`opioide`

## 方法の版

簡略Apfel 1999：4因子、0–4、Koivurantaモデルではない

## 記載された計算式

各因子1点：女性、非喫煙、術後悪心・嘔吐または乗り物酔いの既往、術後オピオイド。

## 限界・対象集団

1999年の簡略化Apfelスコアは、制吐薬の予防投与を受けずに吸入麻酔を受けた成人で、最初の24時間の悪心または嘔吐について研究されました。原コホートの確率は、小児、他の麻酔手技、すでに予防投与を受けている人に自動的に再較正されるわけではありません。制吐方針には専用の評価とガイドラインが必要です。

## 参考文献

- [Apfel CC et al. A simplified risk score for predicting postoperative nausea and vomiting: conclusions from cross-validations between two centers. Anesthesiology, 1999.](https://doi.org/10.1097/00000542-199909000-00022)

- [Gan TJ et al. Fourth consensus guidelines for the management of postoperative nausea and vomiting. Anesth Analg, 2020.](https://doi.org/10.1213/ANE.0000000000004833)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 記録された結果

以下の情報は、合成例に対する手法の出力を保持したものです。独立した臨床的検証を示すものではありません。

### 1

PONVのリスクは約10%

他の因子がない限り、予防投与は通常不要。


### 2

PONVのリスクは約39%

異なるクラスの制吐薬2剤による予防。


### 3

PONVのリスクは約79%

3～4の介入による多面的予防；全静脈麻酔を考慮する。

