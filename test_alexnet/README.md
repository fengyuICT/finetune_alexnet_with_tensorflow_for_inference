![](https://zenodo.org/badge/DOI/10.5281/zenodo.1037359.svg)

# AlexNet Use for Inference
Most code is forked from kratzert

## Finetune AlexNet with Tensorflow
Please check [kratzert project](https://github.com/kratzert/finetune_alexnet_with_tensorflow) and his blog. I just reorganize his code in .ipynb and make it execute correct. (If infringement, I will remove this code)

## Requirements 
-Opencv (Use command "conda install -c menpo opencv" to install it]

## Usage

```
python test_alexnet.py [--show-image 1]
```

## Result

0.00304102897644s  
Class: llama, probability: 0.9984  
0.00399899482727s  
Class: zebra, probability: 1.0000  
0.00291013717651s  
Class: sea lion, probability: 0.9834  

Alexnet inference: 3ms/per image.(Run on Titan V, cuda9, cudnn7)
