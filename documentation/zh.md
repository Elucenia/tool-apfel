<!-- ELUCENIA technical documentation · apfel · zh · no clinical/professional/rights approval -->

# Apfel 评分（术后恶心呕吐）

[条件、来源与许可](https://elucenia.org/zh/tools/apfel)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 女性

`fem`

### 不吸烟者

`naofuma`

### 术后恶心呕吐或晕动症史

`historia`

### 预计术后使用阿片类药物

`opioide`

## 方法版本

简化Apfel 1999：4因素，0–4；不是Koivuranta模型

## 已记录的公式

各因素1分：女性、不吸烟、既往术后恶心呕吐或晕动病、术后阿片使用。

## 限制与适用人群

1999年的简化Apfel评分在接受吸入麻醉、未使用预防性止吐药的成人中研究，结局为最初24小时的恶心或呕吐。原始队列的概率不会自动针对儿童、其他麻醉技术或已接受预防者重新校准。止吐策略须依据专门的评估与指南。

## 参考文献

- [Apfel CC et al. A simplified risk score for predicting postoperative nausea and vomiting: conclusions from cross-validations between two centers. Anesthesiology, 1999.](https://doi.org/10.1097/00000542-199909000-00022)

- [Gan TJ et al. Fourth consensus guidelines for the management of postoperative nausea and vomiting. Anesth Analg, 2020.](https://doi.org/10.1213/ANE.0000000000004833)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

术后恶心和呕吐风险约为10%

一般无需预防，除非存在其他因素。


### 2

术后恶心和呕吐风险约为39%

使用2种不同类别的止吐药进行预防。


### 3

术后恶心和呕吐风险约为79%

采用3至4项干预的多模式预防；考虑全凭静脉麻醉。

