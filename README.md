# Meta Pattern Concern Score

**The paper has been accepted for publication at 2023 IEEE International Conference on Systems, Man, and Cybernetics (SMC'23).**

Commonly used two types of learning objectives respectively from confusion matrix and loss function have different advantages in explainability and mathematical completeness, while they struggle in different dilemmas like the insensitivity to slight improvements and the lack of customizability in different tasks.

In order to achieve both of their advantages and avoid their weaknesses, we propose a novel metric named **Meta Pattern Concern Score (MPCS)** based on an abstract representation of the probabilistic prediction and targeted processing of negative classes, which approaches the cross entropy loss to inherit its theoretical completeness, but allows people to customize explainable requirements to reduce real-world dangerous cases. 

At the same time, this is realized without significantly violating the traditional objectives. For instance, it can be used to find the ideal model significantly reducing the number of dangerous misclassification cases by just slightly sacrificing its training accuracy, or be directly attached to the loss function to train a new model outperforming the original one with lower MPCS value and also fewer number of dangerous cases.
