# はじめに
* このgithubは統計検定準1級の合格を目指す方を対象としています。

# コンテンツの紹介
* 電子ノートをそのまま公開しています。
* 一部グラフを使った理解のためPythonのnotebookを公開しています。
* すべての資料は管理人が準1級合格および統計学の勉学のために記述した資料です。

## コンテンツ
* 書籍「日本統計学会公式認定 統計検定準1級 公式問題集」の解説
  * 問題集の解答に関する行間の記述などを記載しています。
* 書籍「日本統計学会公式認定 統計検定準1級対応 統計学実践ワークブック 第1版」の自作ノート
  * 全章で特に気になった部分や理解が難しかった部分を中心にノートを公開しています。
  * 自作の演習問題も一部含まれています。
  * ワークブック（WB）と一緒にノートが読まれることを想定しています。

# 章の説明
- 01: [事象と確率](./grade1semi_WB/chapter_1/)
- 02: [確率分布と母関数](./grade1semi_WB/chapter_2/)
- 03: [分布の特性値](./grade1semi_WB/chapter_3/)
  - [確率分布毎の歪度と尖度の可視化Notebook](./src/KurtosisAndShapSkewness.ipynb)
- 04: [変数変換](./grade1semi_WB/chapter_4/)
- 05: [離散型分布](./grade1semi_WB/chapter_5/)
- 06: [連続型分布と標本分布](./grade1semi_WB/chapter_6/)
- 07: [極限定理、漸近理論](./grade1semi_WB/chapter_7/)
- 08: [統計的推定の基礎](./grade1semi_WB/chapter_8/)
- 09: [区間推定](./grade1semi_WB/chapter_9/)
- 10: [検定の基礎と検定法の算出](./grade1semi_WB/chapter_10/)
- 11: [正規分布に関する検定](./grade1semi_WB/chapter_11/)
- 12: [一般の分布に関する検定法](./grade1semi_WB/chapter_12/)
- 13: [ノンパラメトリック法](./grade1semi_WB/chapter_13/)
- 14: [マルコフ連鎖](./grade1semi_WB/chapter_14/)
- 15: [確率過程の基礎](./grade1semi_WB/chapter_15/)
- 16: [重回帰分析](./grade1semi_WB/chapter_16/)
- 17: [回帰診断法](./grade1semi_WB/chapter_17/)
- 18: [質的回帰](./grade1semi_WB/chapter_18/)
- 19: [回帰分析その他](./grade1semi_WB/chapter_19/)
- 20: [分散分析と実験計画法](./grade1semi_WB/chapter_20/)
- 21: [標本調査法](./grade1semi_WB/chapter_21/)
- 22: [主成分分析](./grade1semi_WB/chapter_22/)
- 23: [判別分析](./grade1semi_WB/chapter_23/)
- 24: [クラスター分析](./grade1semi_WB/chapter_24/)
- 25: [因子分析・グラフィカルモデル](./grade1semi_WB/chapter_25/)
- 26: [その他の多変量解析法](./grade1semi_WB/chapter_26/)
- 27: [時系列解析](./grade1semi_WB/chapter_27/)
- 28: [分割法](./grade1semi_WB/chapter_28/)
- 29: [不完全データの統計処理](./grade1semi_WB/chapter_29/)
- 30: [モデル選択](./grade1semi_WB/chapter_30/)
- 30: [ベイズ法](./grade1semi_WB/chapter_31/)
- 31: [シミュレーション](./grade1semi_WB/chapter_32/)

# 出題分野
* ChatGPTに出題範囲を渡してカテゴリー分けがされています。

| カテゴリ | 小項目 | 主な内容・キーワード例 |
|----------|--------|-------------------------|
| **1. 確率と確率分布** | 事象と確率 | 確率計算、独立性、条件付き確率、ベイズの定理、包除原理 |
| | 確率関数・分布関数 | 確率関数、密度関数、同時・周辺・条件分布、累積分布、生存関数 |
| | 母関数 | モーメント母関数、確率母関数 |
| | 分布の特性 | モーメント、歪度、尖度、分位点、条件付き期待値・分散、相関係数 |
| | 変数変換 | 変数変換、線形結合の分布 |
| | 極限定理・漸近理論 | 大数の法則、中心極限定理、デルタ法、極値分布、正規近似 |
| | 離散型分布 | 一様、ベルヌーイ、二項、超幾何、ポアソン、幾何、負の二項、多項 |
| | 連続型分布 | 一様、正規、指数、ガンマ、ベータ、コーシー、対数正規、多変量正規 |
| | 標本分布 | t分布、カイ二乗分布、F分布（非心含む） |
| **2. 統計的推測** | 推定法と統計量 | 最尤法、モーメント法、最小二乗法、十分統計量、順序統計量 |
| | 推定の性質 | 不偏性、一致性、有効性、ガウス・マルコフ、クラメール・ラオ不等式 |
| | 区間推定 | 信頼区間、信頼係数、被覆確率、片側限界、2標本区間推定 |
| | 漸近的性質 | フィッシャー情報量、漸近正規性、ジャックナイフ、K-L情報量 |
| | 検定の基礎 | 仮説、P値、棄却域、検定力、検出力曲線、サンプルサイズ、多重比較 |
| | 検定理論 | ネイマン・ピアソン、尤度比、スコア検定、ワルド検定、正確検定 |
| | 正規分布検定 | 母平均、母分散、2標本検定、母相関係数の検定 |
| | 一般分布検定 | 二項検定、ポアソン検定、適合度検定 |
| | ノンパラメトリック法 | ウィルコクソン、並べ替え検定、符号付き順位検定、クラスカル・ウォリス検定 |
| **3. 多変量解析法** | 主成分分析 | 主成分スコア、主成分負荷量、寄与率、累積寄与率 |
| | 判別分析 | 線形判別、2次判別、SVM、ROC、AUC、混同行列 |
| | クラスター分析 | 階層型、k-means、距離行列、デンドログラム |
| | 因子分析・共分散構造分析 | パス解析、因果図、潜在変数、因子の回転 |
| | その他多変量法 | 多次元尺度法、正準相関、対応分析、数量化理論（I〜III類） |
| **4. 種々の応用** | 回帰分析 | 重回帰、残差分析、変数選択、GLS、多重共線性、L1正則化、ロジスティック・プロビット回帰、一般化線形モデル、比例ハザード、NN |
| | 分散分析・実験計画法 | 一元配置、二元配置、交互作用、直交配列、乱塊法 |
| | 標本調査法 | 有限母集団、抽出法、有限修正 |
| | 時系列解析 | ARIMA、自己相関、偏自己相関、定常性、状態空間モデル、ペリオドグラム |
| | マルコフ連鎖・確率過程 | 推移確率、既約性、定常分布、ランダムウォーク、ポアソン過程、ブラウン運動 |
| | 分割表の解析・モデル | オッズ比、ファイ係数、残差分析、対数線形モデル、グラフィカルモデル |
| | 欠測値処理 | 欠測メカニズム、EMアルゴリズム |
| | モデル選択 | 情報量規準、AIC、交差検証 |
| | ベイズ法 | 事前・事後分布、階層ベイズ、MCMC、ギブスサンプリング、MH法 |
| | シミュレーション・計算統計 | ブートストラップ、ジャックナイフ、乱数生成、MCMC、モンテカルロ法 |

# セキュリティ
* セキュリティに関する報告や問い合わせは [SECURITY.md](./SECURITY.md) をご覧ください。