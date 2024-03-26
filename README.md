# ハイパーヒューリスティックの研究について

　　　　　　　　　　　　　　　　　　　　　　　  曹洋　

## １、最近読んだ論文と感想

最近様々なハイパーヒューリスティックに関する論文を読みました。まずは「[A GA-Based Method to Produce Generalized Hyper-heuristics for the 2D-Regular Cutting Stock Problem](https://gpbib.pmacs.upenn.edu/gecco2006/docs/p591.pdf)」よりGAを使っていくつの部品の配置方法（ヒューリスティックス層）を制御して、 Cutting Stock problem (CuSP) を解決しています。この論文はGAでヒューリスティックスとCutting Stock problemを組み合わせして、効率かつ底計算コストでCutting Stock problemを解決出来ました。この論文からハイパーヒューリスティック（メタ）よりヒューリスティックスを制御することがわかりました。

また、「[A hyper-heuristic for improving the initial population of whale optimization algorithm](https://www.sciencedirect.com/science/article/abs/pii/S0950705119300632)」よりDEを使って、 Whale Optimization Algorithm (WOA)のopposition-based learning (OBL) とchaotic maps (CM)を制御して、WOAを改良しました。この論文から**ハイパーヒューリスティックはヒューリスティックスを制御することだけではなくて、ヒューリスティックスのパラメーターと仕組みも制御できることがわかりました。**

そして、「[Hyper-heuristics: A survey and taxonomy](https://www.sciencedirect.com/science/article/pii/S0360835223008392)」から最近ハイパーヒューリスティックの研究動向を了解できました。ハイパーヒューリスティックの上層はメタヒューリスティックスと機械学習で構成することができます。そして、もしアルゴリズムAはある問題で性能がアルゴリズムBを超えている場合、アルゴリズムBは他の問題でアルゴリズムBを超えることができます。**このことよりハイパーヒューリスティックはよく多目的最適化に使われています。**

## ２、ハイパーヒューリスティックの今後の研究について

ハイパーヒューリスティックスのヒューリスティックス選択方法において、よくメタヒューリスティックス（進化計算）と機会学習を使われています。この部分において、出ている研究が多いですので、改良することが難しいと思います。**今後の研究について、ハイパーヒューリスティックスの応用研究においてもしかして成果が出やすいと思います。例えば、ハイパーヒューリスティックスでいくつのヒューリスティックスを制御し、機械学習の多目的最適化を実施します。** 但し、私多目的最適化を行ったことがないですので、多目的最適化について簡単な勉強が必要だと思います。また、機械学習の多目的最適化を行う時に下層のヒューリスティックスの手法の選択にも注意する必要があります。
