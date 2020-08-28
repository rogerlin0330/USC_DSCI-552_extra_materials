# Extra Materials for The USC DSCI-552 Lecture

Hello Class,

The source of the following materials is the notes that I wrote down before after I learned from some other extra materials during the time that I took this course. Now I am going to reorganize them using LaTex and then share with you guys. Most of them are some mathematical proofs corresponding to the topics discussed in lectures, and it is not mandatory for learning in this course since the audiences of this course have varied backgrounds. However, I am sure that some of you are curious about what is the mathematical principles behind, and therefore I want to share the materials.

New content may be added to this post or old content in this post may be updated during the whole semester. Please checkout periodically if you are interested in it, and please let me know if there are any questions.

1. Lesson 1's extra material: [Bias-Variance_Trade-Off.pdf](<./Bias-Variance Trade-Off.pdf>)

2. Lesson 2's extra material: [Linear_Regression.pdf](<./Linear Regression.pdf>)

3. Lesson 3's extra material: [Logistic_Regression.pdf](<./Logistic Regression.pdf>)

4. Lesson 6's extra materials:

   - [https://online.stat.psu.edu/stat508/lesson/11/11.8](https://online.stat.psu.edu/stat508/lesson/11/11.8) (11.8.1 to 11.8.4) - cost complexity pruning.

   - [Decision_Tree.pdf](<./Decision Tree.pdf>) - the advantages of the tree-based method and comparing some commonly used loss functions in the tree-based method (from CS229 at Standford).
   - [Ensemble_Method.pdf](<./Ensemble Method.pdf>) - analyze bagging and boosting from the bias-variance trade-off perspective (from CS229 at Standford).

5. Lesson 7's extra material: [SVM.pdf](./SVM.pdf)

6. Lesson 8's extra material: [PCA.pdf](./PCA.pdf)

7. Lesson 10's extra materials:

   - Backpropagation - [https://mattmazur.com/2015/03/17/a-step-by-step-backpropagation-example/](https://mattmazur.com/2015/03/17/a-step-by-step-backpropagation-example/)
   - Activation Functions - [https://medium.com/the-theory-of-everything/understanding-activation-functions-in-neural-networks-9491262884e0](https://medium.com/the-theory-of-everything/understanding-activation-functions-in-neural-networks-9491262884e0) and [https://towardsdatascience.com/comparison-of-activation-functions-for-deep-neural-networks-706ac4284c8a](https://towardsdatascience.com/comparison-of-activation-functions-for-deep-neural-networks-706ac4284c8a)
   - Other concepts are worth to explore:
     - How to initialize the weight matrix properly? What's the issue if we initialize our weight matrix as a zero-matrix?
     - What is batch gradient descent, mini-batch gradient descent, and stochastic gradient descent?
     - How to make the gradient descent faster by using a larger learning rate without facing the divergent issue? (To explore, one needs to understand the _exponentially weighted average_, _RMSprop_, _momentum_, and the _Adam_ algorithm)
     - How to prevent overfitting? (By getting more data, data argumentation, early stopping, and regularization)
     - How to do regularization in a neural network? (Two common ways: L2-regularization with the Frobenius-Norm and the Dropout regularization. For the latter one, one of the common implementations is the _inverted dropout_)
     - Why do we need to normalize the input for a neural network?
     - What is gradient exploding or gradient vanishing, and how to solve them properly? (Try to Google the Xavier initialization and Yoshua Bengio)
     - What is the learning rate decay?
     - The local optimal issue in neural networks (Using a larger learning rate with the Adam algorithm to get rid of the saddle point quickly).

8. Lesson 11's extra material: [Hidden_Markov_Model.pdf](<./Hidden Markov Model.pdf>) (from CS229 at Standford)

Other materials for machine learning:

1. [http://www.deeplearningbook.org/](http://www.deeplearningbook.org/)

2. [EM_Algorithm.pdf](<./EM Algorithm.pdf>) (from CS229 at Standford)

3. Derivative for Cross-Entropy: [https://peterroelants.github.io/posts/cross-entropy-softmax/](https://peterroelants.github.io/posts/cross-entropy-softmax/)

4. Other optimization methods except for gradient descent, e.g. the _Newton method_, the _Quasi-Newton method (DFP, BFGS)_, _conjugate gradient_, etc. How to address the singular-matrix issue during optimization (e.g. optimizing the cost function of logistic regression, etc.)
