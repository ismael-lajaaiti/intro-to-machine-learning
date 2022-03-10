# Introduction to Machine Learning

Short interactive course to introduce basics of Machine Learning.

## Expected features
- [ ] Explain the basics of Machine Learning 
    - [ ] What is Machine Learning? Explain main concepts (e.g. gradient descent, overfitting)
    - [ ] Where to use Machine Learning? Present Machine Learning frameworks (Tensorflow vs. Torch)
    - [ ] When to use Machine Learning? Conditions to use Machine Learning (e.g large dataset)
    - [ ] Who is using Machine Learning? Give examples of uses of Machine Learning in different fields
    - [ ] Why to use Machine Learning? 
    - [x] How to use Machine Learning? see `.Rmd` file
- [x] Provide an interactive notebook to create and train simple neural network
- [ ] Give references to go further

Work in progres....

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

## References: 
- [Torch framework for R](https://torch.mlverse.org/)  (with [the example that inspired this introduction](https://torch.mlverse.org/start/guess_the_correlation/))
- [Introduction to Machine Learning by M. Pichler and F. Hartig](https://theoreticalecology.github.io/machinelearning/introduction.html)
- Add more references...
