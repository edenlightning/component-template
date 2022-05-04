<div align="center">    

 # Your Component Name     

**Tagline: Assume you never heard of the product, should speak out.**

 ![Project gif](https://media.giphy.com/media/WQH7pj43rMzqFuB1xm/giphy.gif)
 
 ![CI testing](https://github.com/PyTorchLightning/deep-learning-project-template/workflows/CI%20testing/badge.svg?branch=master&event=push)

</div>
 
## Description   
What it does  

## Install
```bash
lightning install my-component
 ```   
 
## How to use   
```python
from project.datasets.mnist import mnist
from project.lit_classifier_main import LitClassifier
from pytorch_lightning import Trainer

# model
model = LitClassifier()

# data
train, val, test = mnist()

# train
trainer = Trainer()
trainer.fit(model, train, val)

# test using the best model!
trainer.test(test_dataloaders=test)
```

### Citation   
```
@article{YourName,
  title={Your Title},
  author={Your team},
  journal={Location},
  year={Year}
}
```   
