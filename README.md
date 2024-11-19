
# Use of Optimization Algorithms for BLM5109 Collective Learning Course at YTU

## Project Details
> **Description:** Use of Optimization Algorithms (Stochastic Gradient Descent, Stochastic Gradient Descent with Momentum and Stochastic Adam) and 5 Different Initial Weight on Image and Text Datasets
> **Course Name:** BLM5109 - Collective Learning  
> **Course Url:** http://bologna.yildiz.edu.tr/index.php?r=course/view&id=6047&aid=3  
> **Course Page:** https://sites.google.com/view/mfatihamasyali/kolektif-%C3%B6%C4%9Frenme  

## Installation
**Step-1:** Create Env. 
```
conda create --name "cl_env" python=3.9  
conda activate cl_env  
python -V
```
**Step-2:** Install Libraries & Frameworks
```
# https://jupyter.org/install
pip install jupyterlab

# https://www.tensorflow.org/install
pip install tensorflow

# https://pytorch.org/
pip install torch torchvision torchaudio

# pip freeze pyliblist_20241107.txt
```

**Step-3:** Start Jupyter IDE
```
# Start Jupyter Lab / Notebook
jupyter lab
jupyter notebook
```

## Datasets
    - CIFAR 10: https://www.cs.toronto.edu/~kriz/cifar.html
    - AG News: http://groups.di.unipi.it/~gulli/AG_corpus_of_news_articles.html

## Preprocess & Modelling
    - Image Dataset
      - Model Arch.: DNN Model
      - Preprocess: Normalization
      - Code: OptTechniqueswithImageData.ipynb  

    - Text Dataset
      - Model Arch.: DNN Model
      - Preprocess: Text Preprocess, Tokenizer and Padding
      - Code: OptTechniqueswithTextData.ipynb

## Contact
    - Ahmet Ugur - 23501027  
    - Metin Uslu - 235B7014