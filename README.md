A simple platform for Plant Disease Detection

## Features

- Plant disease detection (several different types of plants applicapble)
- Information about different crops

## Tech Stack

**ML/DL:** Tensorflow, Keras, Scikit

**Web:** Flask, Bootstrap

## Installation
#### ML/DL

'cnn' folder contains all the notebooks and models related to plant disease classification.

#### Web

```bash
  python3 -m venv venv
  cd webapp
  pip3 install -r requirements.txt
  python3 setup.py
```
## Results

| Architectures|Training Accuracy|Testing Accuracy|Validation Accuracy|
|:---|:---:|:---:|:---:|
|VGG16|92.18|91.33|91.78|
|ResNet50|92.02|85.41|79.53|
|EfficientNetV2|96.06|95.53|95.83|

