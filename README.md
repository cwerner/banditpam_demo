# BanditPAM Demo
Code for the BanditPAM demo of our [Alpine Data Lovers](https://www.meetup.com/alpine-data-lovers) meetup, held on 2022-01-19 at KIT Campus Alpin, Garmisch-Partenkirchen, Germany.

**Paper discussion: Tiwari et al., 2020: Almost Linear-Time k-medoids Clustering via Multi-Armed Bandits** 

**NOTE:** The first two examples are right from the authors (with minor tweeks)

Original References: [[Paper]](https://proceedings.neurips.cc/paper/2020/file/73b817090081cef1bca77232f4532c5d-Paper.pdf), [[Blog]](https://ai.stanford.edu/blog/banditpam/), [[GitHub Code]](https://github.com/ThrunGroup/BanditPAM)


## Installation ⚙️  

- Create an environment and activate it
- `pip install -r requirements.txt`
- [optional: create jupyter kernel]  
```python -m ipykernel install --user --name banditpam_demo --display-name "BanditPAM"```

For general installation ifo see [here](https://github.com/ThrunGroup/BanditPAM#install-the-repo-and-its-dependencies). In case of issues also check the [platform specific installation guides](https://github.com/ThrunGroup/BanditPAM#platform-specific-installation-guides) of the authors. As the python package sits on top of a C++ library there might be issues if the wheels don't match your setup and python tries to build from source...

## Basic example

K-means vs. k-medoids clustering  
[[notebook]](01_Simple_Demo.ipynb)

## MNIST example

Clustering of MNIST digits without an embedding  
[[notebook]](02_MNIST_Demo.ipynb)

## Image example

Image clustering example to demonstrate the usefulness of k-medoids for interpretability  
[[notebook]](03_Image_Demo.ipynb)
