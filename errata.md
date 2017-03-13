# 『ゼロから作る Deep Learning』の正誤表

下記の誤りがありました。お詫びして訂正いたします。

本ページに掲載されていない誤植など間違いを見つけた方は、[japan＠oreilly.co.jp](<mailto:japan＠oreilly.co.jp>)までお知らせください。

### 第8刷まで
|頁               |誤  |正  |
|:--              |:-- |:-- |
|3章 P.56 l.19    |行列`A`の1次元目と行列`C`の0次元目の次元数が一致していない、 |行列`A`の1次元目と行列`C`の0次元目の次元の要素数が一致していない、 |
|4章 P.93 l.3     |また、教師データは10次元のデータです。 |また、教師データは10列のデータです。 |
|6章 P.189 図6-17 |<img src="https://raw.githubusercontent.com/oreilly-japan/deep-learning-from-scratch/images/fig06_17-old.png" alt="誤"> |<img src="https://raw.githubusercontent.com/oreilly-japan/deep-learning-from-scratch/images/fig06_17-new.png" alt="正"> |
|7章 P.237 l.6    |LeNetが今から20年以上も前に提案された   |LeNetが今から20年近くも前に提案された   |
|7章 P.237 l.9    |LeNetが世に出てから20年以上が経過して、 |LeNetが世に出てから20年近くが経過して、 |

### 第7刷まで

|頁              |誤  |正  |
|:--             |:-- |:-- |
|1章 P.17 図1-3  |<img src="https://raw.githubusercontent.com/oreilly-japan/deep-learning-from-scratch/images/fig01_3-old.png" alt="誤">  |<img src="https://raw.githubusercontent.com/oreilly-japan/deep-learning-from-scratch/images/fig01_3-new.png" alt="正"> |
|2章 P34 L.13    |第2層目の入力はyを出力する。 |第2層目のニューロンはyを出力する。 |
|4章 P.91 最終行 |k次元目 |k番目 |
|4章 P.93 L.2    |784次元 |784列 |
|4章 P.111 L.9   |`[[ 0.47355232, 0.9977393 , 0.84668094],`   |`[[ 0.47355232 0.9977393 0.84668094]` |
|4章 P.111 L.10  |　`[ 0.85557411, 0.03563661, 0.69422093]])` |　`[ 0.85557411 0.03563661 0.69422093]]` |
|4章 P.111 L.15  |`[ 1.13282549 0.66052348 1.20919114]`       |`[ 1.05414809 0.63071653 1.1328074]` |
|5章 P.161 L.21  |`(x_train, t_train), (x_test, t_test) = load_mnist(normalize=True)` |`(x_train, t_train), (x_test, t_test) = \`<br>　　`load_mnist(normalize=True, one_hot_label=True)` |
|6章 P.200 L.8   |「10 の階乗」 |「10 のべき乗」 |
|7章 P.232 L.6,7 |`self.layers['Affine2'] = Affine(self.params['W3'],`<br>　　　　　　　　　　　　　　　`self.params['b3'])` |`self.layers['Affine2'] = Affine(self.params['W3'],`<br>　　　　　　　　　　　　　　　`self.params['b3'])`<br><br>`self.last_layer = SoftmaxWithLoss()` |

### 第5刷まで

|頁             |誤  |正  |
|:--            |:-- |:-- |
|2章 P.29 L.3   |**図2-5**の真理値表を満たします。 |**図2-4**の真理値表を満たします。 |
|2章 P.33 L.19  |XORは、**図2-12**に示すような多層構造のネットワークです。 |XORは、**図2-13**に示すような多層構造のネットワークです。 |
|3章 P.56 L.21  |つまり、多次元配列の積では、2つの行列で対応する次元を一致させる必要があるということです。 |つまり、多次元配列の積では、2つの行列で対応する次元の要素数を一致させる必要があるということです。 |
|3章 P.78 L.25  |上の結果から、対応する配列の次元数が一致していることを確認しましょう |上の結果から、多次元配列の対応する次元の要素数が一致していることを確認しましょう |
|3章 P.78 L.27  |次元配列の対応する次元数が一致していますね。 |次元配列の対応する次元の要素数が一致していますね。 |
|3章 P.79 L.2   |10次元の配列が出力されるという流れになっています。 |1次元の配列（要素数10）が出力されるという流れになっています。 |
|4章 P.106 L.8  |どこに最小値を取る場所があるのか検討がつきません。 |どこに最小値を取る場所があるのか見当がつきません。 |
|4章 P.114 L.29 |`y = predict(x)` |`y = self.predict(x)` |
|4章 P.118 L.4  |`(x_train, t_train), (x_test, t_test) = load_mnist(normalize=True)` |`(x_train, t_train), (x_test, t_test) = \`<br>　　`load_mnist(normalize=True, one_hot_label=True)` |
|4章 P.120 L.11 |`(x_train, t_train), (x_test, t_test) = load_mnist(normalize=True)` |`(x_train, t_train), (x_test, t_test) = \`<br>　　`load_mnist(normalize=True, one_hot_label=True)` |
|5章 P.147 L.20 |対応する次元数を一致させるというのがポイントです。 |対応する次元の要素数を一致させるというのがポイントです。 |
|5章 P.147 L.21 |対応する次元数を一致させる必要があります。 |対応する次元の要素数を一致させる必要があります。 |
|5章 P.147 図5-23のキャプション |図5-23 行列の内積では、対応させる次元数を一致させる |図5-23 行列の内積では、対応する次元の要素数を一致させる |
|5章 P.150 L.1  |行列の内積では、対応する次元数を一致させる必要があり、 |行列の内積では、対応する次元の要素数を一致させる必要があり、 |
|5章 P.150 図5-26のキャプション |図5-26 行列の内積（「dot」ノード）の逆伝播は、行列の対応する次元数を一致させるように内積を |図5-26 行列の内積（「dot」ノード）の逆伝播は、行列の対応する次元の要素数を一致させるように内積を |
|6章 P.197 図6-23 |<img src="https://raw.githubusercontent.com/oreilly-japan/deep-learning-from-scratch/images/fig06_23-old.png" alt="誤"> |<img src="https://raw.githubusercontent.com/oreilly-japan/deep-learning-from-scratch/images/fig06_23-new.png" alt="正"> |

### 第4刷まで

|頁                |誤     |正     |
|:--               |:--    |:--    |
|目次、5章、索引   |連鎖率 |連鎖律 |
|4章 P.111 L.23    |続いて、勾配を求めてみましょう。これまでどおり、`numerical_gradient(f, x)`を使って勾配を求めます。 |続いて、勾配を求めてみましょう。これまでどおり、`numerical_gradient(f, x)`を使って勾配を求めます（ここで定義した`f(W)`という関数の引数`W`は、ダミーとして設けたものです。これは、`numerical_gradient(f, x)`が内部で`f(x)`を実行するため、それと整合性がとれるように`f(W)`を定義しました）。 |
|7章 P.236 L.10,14 |1989年 |1998年 |

### 第3刷まで

|頁           |誤  |正  |
|:--          |:-- |:-- |
|3章 P.76 L.4   |`ch03/nueralnet_mnist.py` |`ch03/neuralnet_mnist.py` |
|4章 P.89 L.19  |`>>> y = [0.1, 0.05, 0.1, 0.0, 0.05, 0.1, 0.0, 0.6, 0.5, 0.0]`<br>`>>> mean_squared_error(np.array(y), np.array(t))`<br>`0.72250000000000003` |`>>> y = [0.1, 0.05, 0.1, 0.0, 0.05, 0.1, 0.0, 0.6, 0.0, 0.0]`<br>`>>> mean_squared_error(np.array(y), np.array(t))`<br>`0.59750000000000003` |
|4章 P.91 L.15  |`>>> y = [0.1, 0.05, 0.1, 0.0, 0.05, 0.1, 0.0, 0.6, 0.5, 0.0]`<br>`>>> cross_entropy_error(np.array(y), np.array(t))`<br>`2.3025850919940458` |`>>> y = [0.1, 0.05, 0.1, 0.0, 0.05, 0.1, 0.0, 0.6, 0.0, 0.0]`<br>`>>> cross_entropy_error(np.array(y), np.array(t))`<br>`2.3025840929945458` |
|4章 P.117 L.29 |`ch04/train_nueralnet.py` |`ch04/train_neuralnet.py` |
|4章 P.118 L.7  |`# ハイパーパラメータ`<br>`iters_num = 10000`<br>`batch_size = 100`<br>`learning_rate = 0.1` |`# ハイパーパラメータ`<br>`iters_num = 10000`<br>`train_size = x_train.shape[0]`<br>`batch_size = 100`<br>`learning_rate = 0.1` |
|5章 P.127 L.23 |各ノードでは単純な計算をに集中することで、 |各ノードでは単純な計算に集中することで、 |
|5章 P.162 L.19 |`ch05/train_nueralnet.py` |`ch05/train_neuralnet.py` |

### 第2刷まで

|頁           |誤  |正  |
|:--          |:-- |:-- |
|2章 P.24 L.1 |両方が1のときだけ0を出力し、それ以外は0を出力します。 |両方が1のときだけ0を出力し、それ以外は1を出力します。 |

### 第1刷

|頁               |誤  |正  |
|:--              |:-- |:-- |
|7章 P.227 図7-20 |<img src="https://raw.githubusercontent.com/oreilly-japan/deep-learning-from-scratch/images/fig07_20-old.png" alt="誤"> | <img src="https://raw.githubusercontent.com/oreilly-japan/deep-learning-from-scratch/images/fig07_20-new.png" alt="正"> |
