POS(Accuracy) | wsj | answers | newsgroups | reviews | weblogs | emails
--------|--------|-------|--------|-------- | -------- | -------- 
 Shared Task result | 97.76 | 91.79 | 93.81 | 93.11| - | - 
 Original | 98.15 | 94.42 | 95.50 | 95.69| 94.45 | 95.6 
 Preprocessing | 98.15 | 94.78 | 95.98 | 95.93| 94.76 | 96.04 
 
 POS的总体结构是Bi-directional LSTM+CRF，使用CNN提取字向量特征(Chiu&Nichols.2015)
 
 Shared Task result是评测任务中每项的最高值
 
 Original是使用原数据直接测试的结果
 
 Preprocessing是对测试数据处理之后的结果（双引号，URL，Email，否定后缀，连续标点）

 -----
 Biaffine Parser|wsj|wsj|answers|answers|newsgroups|newsgroups|reviews|reviews|weblogs|weblogs|emails|emails
 -----|----|----|----|---|----|----|----|---- | ----|---- | ----|----| 
 --------| LAS | UAS | LAS | UAS | LAS | UAS | LAS | UAS | LAS | UAS | LAS | UAS |
 Shared Task result | 91.88 | 93.88 | 81.15 | 85.86 | 85.85 | 89.10 | 83.86 | 88.31 | - | - | - | - |
 gold POS | 94.43 | 95.55 | 96.92 | 89.73 | 89.78 | 91.71 | 88.21 | 90.59 | 90.75 | 92.50 | 85.04 | 87.58 |
 auto POS | 92.86 | 94.63 | 82.60 | 87.37 | 86.30 | 89.64 | 84.79 | 88.78 | 87.12 | 90.75 | 80.83 | 84.59 |
 auto POS(Preprocessing) | 92.86 | 94.63 | 82.64 | 87.38 | 86.28 | 89.64 | 84.84 | 88.85 | 87.17 | 90.78 | 80.88 | 84.64 |
 
 Shared Task result是评测任务中每项的最高值
 
 gold POS是使用数据中提供的正确分词结果直接测试结果
 
 auto POS是使用上面POS结果，未数据处理的测试结果
 
 auto POS(Preprocessing)是使用上面POS结果并对数据处理之后测试结果（双引号，URL，Email，否定后缀，连续标点）
 
 -----
wsj(LAS)|wsj(UAS)|answers|answers|newsgroups|newsgroups|reviews|reviews|weblogs|weblogs|emails|emails
 ----|----|----|---|----|----|----|---- | ----|---- | ----|----|
 POS | LAS | POS | LAS | POS | LAS | POS | LAS | POS | LAS | POS | LAS |
 95.64 | 85.20 | 95.16 | 86.34 | 95.90 | 87.18 | 95.03 | 87.51 | 95.79 | 88.23 | 95.90 | 85.57 
 
 Sebastian & Barbara.2017(Learning to select data for transfer learning with Bayesian Optimization)
 
 -----
 wsj | answers | newsgroups | reviews | weblogs | emails
--------|-------|--------|-------- | -------- | -------- 
 87.5 | 74.6 | 80.2 | 77.0 | 81.2 | 74.4 
 
 Google Web Treebank LAS Result
 
 Adhiguna et al.2017(Dependency Parsing with LSTMs: An Empirical Evaluation)
