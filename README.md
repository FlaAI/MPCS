# Meta Pattern Concern Score: A Novel Metric for Customizable Evaluation of Multi-classification

## Update

#### September 2022:
- A toy sample program using **Meta Pattern Concern Score** to evaluate a CNN classifier in the MNIST dataset is added for reference in advance.
- The work is in progress at present and the detailed description (as well as a possible technology paper) will be opened to the public soon.


## Abstract

Commonly used two types of metrics respectively based on confusion matrix and loss function have different advantages in flexibility and mathematical completeness, while they struggle in different dilemmas like the insensitivity to slight improvements or the lack of customizability in different tasks. 

We propose a novel metric named **Meta Pattern Concern Score** based on the abstract representation of the probabilistic prediction, as well as the targeted design for processing negative classes in multi-classification and reducing the discreteness of metric value, to achieve advantages of both the two kinds of metrics and avoid their weaknesses. 

Our metric provides customizability to pick out the model for specific requirements in different practices, and make sure it is also fine under traditional metrics at the same time. For instance, it can be designed to select a model to significantly reduce the number of dangerous misclassification cases by only slight sacrificing the training accuracy of the model.
