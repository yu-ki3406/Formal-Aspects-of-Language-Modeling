# Formal-Aspects-of-Language-Modeling

- [Formal Aspects of Language Modeling](https://arxiv.org/pdf/2311.04329)

今の所、教科書を読んで、重要そうだなと思ったところを自分のメモ用で書いています。

text読んでいて、読みたくなった論文
- [A Probability–Quality Trade-off in Aligned Language Models and its Relation to Sampling Adaptors](https://aclanthology.org/2024.emnlp-main.822.pdf)
DPOとかfine-tuningされた言語モデルは学習前の言語モデルの尤度と報酬のトレードオフになってる、それをいい塩梅でどっちを優先するかなどをsamplingできる手法を理論的に、toy problemで実験的にも確認できた。
少し気になることは安全性などを考慮している言語モデルなどでも同じことできるの？

- Local normalization Language modelでbase modelとか学習1step前のKLとか入れたら、Regularized mdpみたいになって解析できる？