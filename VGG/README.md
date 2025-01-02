

## Abstract
This architecture is a further improvement from AlexNet. The depth of this architecture is comparably higher, at 19 layers. This is achieved with the help of using only 3x3 kernels for convolutional layers. This is the minimum size that preserves the notion of "top", "bottom", etc. In this way the model can go deeper, and thus draw better inferences from data, leading to a higher accuracy. Yet, interestingly, this architecture does not use any sort of normalization (for the 19 weight layer version atleast); citing that it did not lead to a substantial increase in performance yet was a burden on computer resources.

## Paper Cited:
For those who are interested in the research paper that this model is based off of, here is a URL:
https://arxiv.org/pdf/1409.1556
