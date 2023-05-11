
# Image Caption Gnerator AI Web APP

Whenever an image appears in front of us our brain is capable of annotating or labeling it. But, what about computers? How can a machine process an image and label it with a highly relevant and accurate caption? It seemed quite impossible a few years back, but now with the enhancement of Computer Vision and Deep learning algorithms, availability of relevant datasets, and AI models, it becomes easier to build a relevant caption generator for an image. Even Caption generation is becoming a growing business in the world, and many data annotation firms are earning billions from this. In this guide, we are going to build one such annotation tool which is capable of generating very relevant captions for the image with the help of transfer learning(Basically pre-trained deep learning model). 


## Documentation

In this web app I used two pretrained model for generating caption for image, for showing result difference between two model for same image
* BLIP
* VIT

Form the captions of BLIP model and VIT model I generate more relatable caption using openAI
## BLIP Model
The BLIP model was proposed in **BLIP: Bootstrapping Language-Image Pre-training** for Unified Vision-Language Understanding and Generation by Junnan Li, Dongxu Li, Caiming Xiong, Steven Hoi.

BLIP is a model that is able to perform various multi-modal tasks including

* Visual Question Answering
* Image-Text retrieval (Image-text matching)
* Image Captioning

## VIT

The Vision Transformer (ViT) model was proposed in An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale by Alexey Dosovitskiy, Lucas Beyer, Alexander Kolesnikov, Dirk Weissenborn, Xiaohua Zhai, Thomas Unterthiner, Mostafa Dehghani, Matthias Minderer, Georg Heigold, Sylvain Gelly, Jakob Uszkoreit, Neil Houlsby. It’s the first paper that successfully trains a Transformer encoder on ImageNet, attaining very good results compared to familiar convolutional architectures.
## Tech Stack

* Python for building web APP
* Streamlit for creating the user interface
* Hugging Face Pretrained model API for image caption generation
* OpenAI API for generating different relatable caption



## Requirements

* Python 3.8 or above
* Streamlit package
* Hugging Face API 
* OpenAI API credentials
* Other necessary Python libraries (see requirements.txt)
## Usage
* Install require Python libraries (see requirements.txt)
* streamlit run main.py this command in terminal
* Navigate to the URL provided after running the Streamlit run main.py
* Upload an image to the Web APP.
* Wait for the AI to generate captions
* Choose the captions that best suit your needs.

