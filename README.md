# Introduction to Machine Learning

Short interactive course to introduce basics of Machine Learning in R with Torch.

## Features
- [Presentation of the basics of Machine Learning](slides-basics-machine-learning.pdf) which:
    - Explains main concepts of Machine Learning (e.g. gradient descent, overfitting)
    - Presents Machine Learning frameworks in R (Tensorflow vs. Torch)
    - Gives examples of uses of Machine Learning in different fields
- [Provide an interactive Rmarkdown to create a simple neural network with Torch](introduction-machine-learning.Rmd) (also available in [pdf](introduction-machine-learning.Rmd.pdf) and [html](introduction-machine-learning.Rmd.html)) which go over the following steps:
    - Cleaning the data
    - Building a deep neural network 
    - Training the neural network 
    - Evaluating performances of the neural network
- Give references to go further (see below)


## Requirements 

The Torch framework needs to be installed to run `introduction-machine-learning.Rmd`. The installation of the different depencies are detailed on the first cells of that file. Otherwise, you can run with `R` the following lines to install the Torch framework:

```
install.packages("torch")
install.packages("torchvision")
``` 

Then to install the dataset run:

```
remotes::install_github("mlverse/torchdatasets")
```

Lastly, to check that Torch is installed correctly, do:

```
library(torch)
torch_tensor(1)
```

## Further reading
- [Torch framework for R](https://torch.mlverse.org/)  (with [the example that inspired the Rmarkdown](https://torch.mlverse.org/start/guess_the_correlation/))
- [PyTorch documentation](https://pytorch.org/docs/stable/index.html) that can complete the incomplete R documentation (if you know a bit about Python, it can be easily transposed in R)
- [Introductory course to Machine Learning by M. Pichler and F. Hartig](https://theoreticalecology.github.io/machinelearning/introduction.html)
