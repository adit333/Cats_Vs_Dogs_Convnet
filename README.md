This is a Convnet trained to classify Cats and Dogs.

Keras was used for building the Deep Neural Network.

I went through several iterations to get the final result:
1) Training a small convnet from scratch - 72% accuracy.
  - Used Data Augmentaion - 82% accuracy.
2) Using a Pretrained VGG16 Convnet:
  - For feature extraction (by freezing the convolution base) - 90% accuracy.
  - Feature extaction and data augmentation - 96% accuracy.
  - Fine-tuning the VGG16 network by training last few layers - 97% accuracy.
  
I then went to produce visualizations of what the networks learned:
- Visulaized immediate activations of the small convenet.
- Visualzied convnet filters of the VGG16 network.
- Visualzing heatmaps of the class activations.
