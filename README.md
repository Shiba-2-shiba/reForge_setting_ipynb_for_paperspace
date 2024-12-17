# reForge_setting_ipynb_for_paperspace

このリポジトリはPaperspaceで、私がカスタムしたDocerイメージを使用したものを前提としています。

##Paperspaceで使用する Docker イメージ

以下の Docker イメージをPaperspaceのコンテナの部分に入力して使用してください：

```bash
shibashiba2/paperspace-gradient-base-pytorch241:v8
```

Dockerイメージを使用する方法については、以下のURLを参考にしてください。

https://note.com/gentle_murre488/n/nb2913ed01a79


## 使用方法

Paperspaceのセルコマンドの実行もしくはターミナルでコマンドを実行して、このリポジトリに公開されているipynbファイルをダウンロードして、ipynbファイル内のコマンドを実行することでForgeを簡単に起動することができます。

手動でノートブックディレクトリに、このリポジトリに公開されているipynbファイルをアップロードして使用しても同様のことができます。

現状のDockerイメージのスクリプトだとモデル②以降のipynbはダウンロードできないのでご注意ください。

詳細は先ほどのURLの記事に記載しています。

ノートブックディレクトリに配置されたら、そのセルコマンドを個々でカスタムして使いやすくしてください。
