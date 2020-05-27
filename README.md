# MSCOCO26K

This project contains the splits of MSCOCO26K image caption dataset, extracted from [MSCOCO](http://cocodataset.org/), for training and testing. The splits are NumPy files including the name of images in the dataset and their corresponding facial expression labels. Using the label files, you can train a new image captioning model without training a facial expression recognition module. Each label consists of seven binary digits defining 'angry', 'disgust', 'fearful', 'happy', 'sad', 'surprised', and 'neutral', respectively. For example, [0. 0. 0. 1. 0. 0. 0.] is the label of 'happy' samples. 

Image captioning is the process of generating a natural language description of an image. Most current image captioning models, however, do not take into account the emotional aspect of an image, which is very relevant to activities and interpersonal relationships represented therein. Towards developing a model that can produce human-like captions incorporating these, we use facial expression features extracted from images including human faces, with the aim of improving the descriptive ability of the model. 

