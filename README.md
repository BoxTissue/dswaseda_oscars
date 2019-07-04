# dswaseda_oscars
Waseda University Data Science Competition Oscars

## 準備
- 頑張ってDockerを入れます
- このレポジトリの取得。datascience-notebookの取得。時間がかかります。重い。
- コンテナの起動
```
$ git clone https://github.com/BoxTissue/dswaseda_oscars.git
$ docker pull jupyter/datascience-notebook
$ docker run -p 9000:8888 --name notebook jupyter/datascience-notebook
```
- ブラウザでlocalhost:9000に接続します
- おわり

## 概要
