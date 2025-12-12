# data_disribution
## 概要
このノートでは導入するデータリストの分布を確認する


# LogitModel概要
## two_choice_logit
### 概要
- logsum部分とメイン部分を同時推定したロジットモデル

### 推定結果
- logsum部分がすべて有意にならない
- 同時推定していないのが原因と予想

## two_choice_logit2
### 概要
- model1の問題を踏まえて，段階推定で実施

### 推定結果
- logsum部
    - 駐輪場料金が悪さをしている可能性

## two_choice_logit3
### 概要
- model2の反省を踏まえて，一旦駐輪場料金を抜くのが吉
- 時間のスケーリングを見直し⇒1分辺りに変更

### 推定結果
- 推定としては，うまくいっている

## two_choice_logit5
### 概要
- 3の反省を受け，段階推定から同時推定に変更
- これにより，各交通手段の影響を明らかにすることができる

## estimate_visualization1
### 概要
two_choice_logit4の推定結果を感度分析している

