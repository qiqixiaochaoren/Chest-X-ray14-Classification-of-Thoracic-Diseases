Chest disease has problems such as small lesion area, easy to be affected by healthy area, and difficult to locate. In order to solve the above problems, this paper proposes a self-correcting feature pyramid network structure, which uses self-correcting convolution to enhance the positional relationship of disease parts on the feature map and between channels, avoiding information interference in disease-free areas, and passing the feature The pyramid structure integrates multi-scale image output features to obtain high-resolution feature maps while accurately localizing chest diseases. At the same time, the frequency channel attention mechanism is introduced to strengthen the network's ability to extract disease location information and suppress the transmission of useless information. Finally, a new loss function is proposed to solve the problem of unbalanced sample distribution. The experimental results on the official Chest X-ray14 dataset show that compared with the traditional chest disease classification algorithm, the algorithm in this paper improves the detection accuracy, and the average AUC value has reached 0.853.
