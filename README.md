# concrete-with-machine-learning

セメント，水，細骨材，粗骨材の単位重量と最大粒径により， [Required strength， Slump]を予測する．（骨材の密度などの変数も追加できるか，簡単化するためにinputをその5つの値に設定した）
The code is implemented to predict concrete strength and slump value from the recipe ratio by machine learning methods.


X values will be determined from Y values using the provisional mix proportion for satisfying the following requirement by JSCE method.

Y values will be random generated.

データセットを簡単的に作成できるように、以下の定義を行った。
  Cement: ASTM Type I (Ordinary Portland cement), Specific gravity of 3.14
  Fine Aggregate: Fineness modulus = 2.80, Specific gravity of 2.55
  Coarse Aggregate: Specific gravity of 2.68
  Water: Specific gravity of 1
