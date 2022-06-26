# Understanding Convolutional Neural Networks

## Visualising CNN's

* Large Convolutional Network models have recently demonstrated impressive classification performance on the ImageNet benchmark. However there is no clear understanding of why they perform so well, or how they might be improved. In this repository, visualization technique that gives insight into the function of intermediate feature layers and the operation of the classifier is given. We also perform an ablation study to discover the performance contribution from different model layers. This enables us to find model architectures that outperform on the ImageNet classification benchmark.
* Project status: working


## Usage

### Screenshots
![image](https://user-images.githubusercontent.com/56218470/175812091-df973a3a-e82c-473b-9ec4-a800bfc4bf5d.png)  

![image](https://user-images.githubusercontent.com/56218470/175812223-a0d02ecf-170d-4981-9fe7-d3329bd0b33a.png)


![image](https://user-images.githubusercontent.com/56218470/175812185-08f9e51e-9cc0-4852-b15c-ee3b87a30f02.png)



### Content

explored large convolutional neural network models, trained for image classification, in a number ways.
First, the paper [1] presented a novel way to visualize the activity within the model. This reveals the features to be far from random, uninterpretable patterns. Rather, they show many intuitively desirable properties such as compositionality, increasing invariance and class discrimination as we ascend the layers. they also showed how these visualization can be used to debug problems with the model to obtain better results.

### Requirements

Pytorch
Opencv-python
Jupyter Notebook



### Run Experiments

    gh repo clone unboxdisease/Visualizing_CNN-s
    cd Visualizing_CNN-s/Experiments
    jupyter notebook

### Reference
[1] Zeiler, Matthew D., and Rob Fergus. "Visualizing and understanding convolutional networks." European conference on computer vision. Springer, Cham, 2014.
