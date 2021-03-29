# text_gcn

The implementation of Text GCN in our paper:

Liang Yao, Chengsheng Mao, Yuan Luo. "Graph Convolutional Networks for Text Classification." In 33rd AAAI Conference on Artificial Intelligence (AAAI-19), 7370-7377


## Require

Python3.6

Tensorflow >= 1.14.0, <1.15

Download data [data_merger](https://drive.google.com/file/d/1sPz-7Rn7iViJ9mvQOZT0F9iKLkVcab61/view?usp=sharing) then rename to _my_custom_data_
## Train custom data

1. Run `python build_graph.py my_custom_data`

2. Run `python train.py my_custom_data`

## Inductive version

An inductive version of Text GCN is [fast_text_gcn](https://github.com/yao8839836/fast_text_gcn), where test documents are not included in training process.
