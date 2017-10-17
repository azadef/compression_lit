# Existing compression techniques
-------------------------------
    
1. Network quantization
-----------------------

- SqueezeNet:
    - Paper: https://arxiv.org/pdf/1602.07360.pdf
    - Code: https://github.com/DeepScale/SqueezeNet (Official, Caffe)
            https://github.com/vonclites/squeezenet (Unofficial, TF)
            https://github.com/avoroshilov/tf-squeezenet (Unofficial, TF)
            + more
    - Status: 

- XNORNet:
    - Paper: https://arxiv.org/pdf/1603.05279.pdf
    - Code:  https://github.com/allenai/XNOR-Net (Official, Torch)
             not supported in TF due to an issue: https://github.com/tensorflow/tensorflow/issues/1592
             https://github.com/AngusG/tensorflow-xnor-bnn (may work)
    - Status: 
    
- MobileNet:
    - Paper: https://arxiv.org/pdf/1704.04861.pdf
    - Code:  https://github.com/tensorflow/models/blob/master/research/slim/nets/mobilenet_v1.py (Official, TF, Object Detection API)
             https://github.com/Zehaos/MobileNet (Unofficial, TF)
    - Status: 
    
2. Network prunning
-------------------

- Deep Roots:
    - Paper: https://arxiv.org/pdf/1605.06489.pdf
    - Code:  https://github.com/facebook/fb.resnet.torch (Official, Torch, ResNet?, should read paper)
             Not found any unofficial TF version yet
    - Status: 
    
- ShuffleNet::
    - Paper: https://arxiv.org/pdf/1707.01083.pdf
    - Code:  https://github.com/jaxony/ShuffleNet
             https://github.com/MG2033/ShuffleNet
    - Status: 

3. Dark Knowledge
-----------------

- Distillation:
    - Paper: https://arxiv.org/pdf/1503.02531.pdf
    - Code:  https://github.com/chengshengchan/model_compression (Unofficial, TF)
             https://github.com/akamaus/mnist-distill (Unofficial, TF)
    - Status: 

- FitNets:
    - Paper: https://arxiv.org/pdf/1412.6550.pdf
    - Code:  https://github.com/adri-romsor/FitNets (Official, Theano + pylearn2)
             https://github.com/lisa-lab/pylearn2/tree/master/pylearn2/scripts/papers/maxout (Official, Theano + pylearn2 , Teacher)
    - Status: 
    
- Adversarial compression:
    - Status: 



Tutorials:
----------

    - http://machinethink.net/blog/compressing-deep-neural-nets/

Interesting Papers:    
-----------

    - Deep Model Compression: https://arxiv.org/pdf/1610.09650.pdf
    - Efficient Inference Engine on Compressed Deep Neural Network: https://arxiv.org/pdf/1602.01528.pdf

Interesting Codes:
-----------

    - Distillation: https://github.com/iRapha/replayed_distillation (Very recent, check later, paper not released yet)
