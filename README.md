# Deep Learning Tensorflow tutorial for MNIST
手書き数字画像データ（MNIST）を用いて画像分類を行なうDeep Learning Demoのjupyter notebookを格納したリポジトリです。
以下のdemo1-3のnotebookがあります。
- Demo1: データが少ない場合の学習
- Demo2: 全てのデータを使った場合の学習
- Demo3: より高精度なモデルを使った学習

## 準備
### python系の準備
- Python3 インストール. [Anaconda3](https://www.continuum.io/downloads)を使うと簡単です。
- pip install tensorflow
- pip install tqdm
- pip install sklearn
- pip install tabulate
- pip install tfgraphviz
- pip install seaborn
- pip install jupyter

### その他必要ライブリの準備
- sudo yum install graphviz

### MNIST 画像データのダウンロード
- cd MNIST_data
- wget http://yann.lecun.com/exdb/mnist/train-images-idx3-ubyte.gz
- wget http://yann.lecun.com/exdb/mnist/train-labels-idx1-ubyte.gz
- wget http://yann.lecun.com/exdb/mnist/t10k-images-idx3-ubyte.gz
- wget http://yann.lecun.com/exdb/mnist/t10k-labels-idx1-ubyte.gz

## 使用方法
- jupyter notebookを起動してブラウザで各Demoのnotebookを参照してください。
- 起動後に標準出力に表示されるtoken付きのURLにブラウザでアクセスしてください。

```
# jupyter notebookの起動方法
$ jupyter notebook

Copy/paste this URL into your browser when you connect for the first time,
to login with a token:
    http://0.0.0.0:5555/?token=c4b740fb703c9d5d5a3f2336825fd078521eb9456d854c48
```
