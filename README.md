# Depth_Estimation

Learning depth information from image is a crucial topic in computer vision.  It is also a problem under the general topic [Geometry learning](http://geometricdeeplearning.com/)  This project meaned to explore and build machine learning model that can output depth or relative depth from input image either in a supervised or unsupervised manner.


## Benchmark datasets
1. Indoor scene: [NYU v2](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html).
2. Outdoor scene: [KITTI](http://www.cvlibs.net/datasets/kitti/eval_depth_all.php).
3. 3D model related: [Make3D](http://make3d.cs.cornell.edu/data.html).

## Relevant papers for depth estimation/prediction

| Paper | Description |
| --- | --- |
| [Learning Depth from Single Images with Deep Neural Network Embedding Focal Length](https://arxiv.org/abs/1803.10039) | Fully supervised method considering varying focal length |
| [Sparse-to-Dense: Depth Prediction from Sparse Depth Samples and a Single Image](https://arxiv.org/abs/1709.07492) | Depth prediction with sparse depth samples augmentation |
| [Depth Map Prediction from a Single Image using a Multi-Scale Deep Network](https://arxiv.org/abs/1406.2283) | Coarse network + fine network (prior work for state-of-art on NYUv2) |
| [Predicting Depth, Surface Normals and Semantic Labels with a Common Multi-Scale Convolutional Architecture](https://arxiv.org/abs/1411.4734) | State-of-art model on NYUv2 |
| [Deeper Depth Prediction with Fully Convolutional Residual Networks](https://arxiv.org/abs/1606.00373) | Another state-of-art model on NYUv2 using ResNet |
