# Azure Databricks notebook sample to visualize and display Decision Tree model

Update version 1.1

Two approach to visualize Decision Tree in Notebook & Azure Databricks Notebook.
* Using Scikit model dot export and covert dot to png approach with Graphviz
* Using Matplotlib to visualize decision tree and export to png approach

Contents
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

![alt text](https://github.com/easonlai/decision-tree-sample/blob/main/git-images/git-image-2.png)


