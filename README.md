# Azure Databricks notebook sample to convert Decision Tree DOT model file to PNG via Graphviz, and then display PNG file.

* decision-tree-sample.ipynb <-- Notebook sample from Mac.
* decision-tree-sample-databricks.ipynb <-- Notebook sample from Azure Databricks.
* decision-tree-sample-databricks.html <-- HTML Export of Notebook sample from Azure Databricks.

## Install Graphviz in Mac
```shell
brew install graphviz
```

## Install Graphviz in Azure Databricks
```shell
%md
sudo apt install python-pydot -y
```

```shell
%md
sudo apt install python-pydot-ng -y
```

```shell
%md
sudo apt install graphviz -y
```

![alt text](https://github.com/easonlai/decision-tree-sample/blob/main/git-images/git-image-1.png)


