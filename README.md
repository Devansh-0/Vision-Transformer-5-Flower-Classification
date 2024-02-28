# Vision Transformers Application in Image Classification

#### Vision Transformers (ViTs) are machine learning models that use self-attention mechanisms to process images. They can be used for image classification, object detection, and semantic image segmentation. The 5 flower dataset ws utilized to understand the working and application of ViT in detail.

### The model produced an accuracy of a whopping 99%.

Attention mechanisms combined with RNNs were the predominant architecture for facing any task involving text until 2017, when a paper was published and changed everything, giving birth to the now widely used Transformers. The paper was entitled “Attention is all you need.”

A Transformer is a deep learning model that adopts the self-attention mechanism, differentially weighting the significance of each part of the input data. Transformers are increasingly the model of choice for NLP problems, replacing RNN models such as long short-term memory (LSTM). 
The Vision Transformer (ViT) model was introduced in 2021 in a conference research paper titled "An Image is Worth 16*16 Words: Transformers for Image Recognition at Scale," published at ICLR 2021. The fine-tuning code and pre-trained ViT models are accessible on Google Research's GitHub. The ViT models were pre-trained on the ImageNet and ImageNet-21k datasets.

Vision transformers have extensive applications in popular image recognition tasks such as object detection, image segmentation, image classification, and action recognition. Moreover, ViTs are applied in generative modeling and multi-model tasks, including visual grounding, visual-question answering, and visual reasoning.

In ViTs, images are represented as sequences, and class labels for the image are predicted, which allows models to learn image structure independently. Input images are treated as a sequence of patches where every patch is flattened into a single vector by concatenating the channels of all pixels in a patch and then linearly projecting it to the desired input dimension.

#### The 5 flower dataset was trained in 5 epochs with a batch size of 32 and close to 85000000 parameters.

![image](https://github.com/Devansh-0/Vision-Transformer-5-Flower-Classification/assets/69781697/ef64375e-3b77-444f-b6d1-7c5916a7425d)

![image](https://github.com/Devansh-0/Vision-Transformer-5-Flower-Classification/assets/69781697/6575d2c2-e9d3-42ec-8630-697e3bfeac3f)

