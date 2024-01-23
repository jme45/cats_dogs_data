# cats_dogs dataset
> A very simple dataset with 5 pictures for training and 5 for cross validation, to see whether an ML model can learn 
> the difference between cats and dogs from very fet datapoints.

## Usage example
```python
import torchvision
from torchvision.transforms import v2
train_dir = "train"
train_set = torchvision.ImageFolder(root=train_dir,
                                    transform=v2.ToTensor())
```
