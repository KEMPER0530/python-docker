# python-docker

## Features

docker で python3 の環境作成

## Requirement

- python3

## Installation

```bash
$ docker-compose up -d
```

## Usage

### コンテナへ接続

```bash
$ docker-compose exec python3 bash
```

### 各種ライブラリをインストール (任意)

```bash
$ python -m pip install numpy
$ python -m pip install pandas
$ python -m pip install matplotlib
$ python -m pip install networkx
$ python -m pip install pyyaml
$ python -m pip install xlsxwriter
$ python -m pip install tornado
```

### python の実行

```bash
$ python ./opt/sample.py 180.0
3.141592653589793
```

## Reference

- [Docker で Python 実行環境を作ってみる](https://qiita.com/jhorikawa_err/items/fb9c03c0982c29c5b6d5)
