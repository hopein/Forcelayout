Name
====

Overview
ばねモデル(力学モデル)のライブラリ


## Example
ノードの名前(画像名)とリソースファイルが含まれたノードの情報と、ノード間のリンクの情報を読み込んで使用する


ノードの定義
HashMap<String, Integer> nodes = new HashMap<>();
nodes.put("ラベルネーム",R.drawable.example);

リンクの定義
HashMap<String, String> links = new HashMap<>();
links.put("ラベルネーム1","ラベルネーム2");

Banemodel.Properties banemodel = Banemodel.with(this);
banemodel.setnodes(nodes);
banemodel.setlinks(links);


## Demo
* `Ctrl + f` : toggle search bar - [gif](https://github.com/kai0masanari/baneVisualizer/blob/master/image.gif)

## VS. 

## Requirement

## Usage