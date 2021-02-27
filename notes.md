# OpenVino (Open Visual inferencing and neural network optimization)

## Optimizations in the Model Optimizer

* It uses the dataset to analyze and validate the network
before applying a number of
generic network optimization techniques.
* Generic optimization includes
    * node merging
    * horizontal fusion
    * batch normalization to scale shift
    * fold scale shift with convolution
    * drop unused layers also known as dropout
    * FP16 to FP32 quantization depending on the processor
    * normalization and Mean operations

## Optimizations in Inference Engine

* Network level optimization: 
* Memory level optimization:
* Kernel level optimization:

Has 2 main components:
* Inference engine runtime
* Inference engine validator
