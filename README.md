## CrackingMachineLearningInterview

These questions are guranteed to be asked in Machine Learning Engineer or ML based interviews for upto 80% of your job interviews. Make sure that you cover and know about machine learning. These questions can Ace your interviews regarding ML even if you are a fresh graduate or upto 5 years of experience.


* GIthub Profile :  [Shafaypro](https://github.com/shafaypro)
* ML Interview Questions repository : [ML interview Repository Link](https://github.com/shafaypro/CrackingMachineLearningInterview "ML Interview Repository")
## Questions

#### Difference between SuperVised and Unsupervised Learning?
        Supervised learning is when you know the outcome and you are provided with the fully labeled outcome data while in unsupervised you are not provided with labeled outcome data. Fully labeled means that each example in the training dataset is tagged with the answer the algorithm should come up with on its own. So, a labeled dataset of flower images would tell the model which photos were of roses, daisies and daffodils. When shown a new image, the model compares it to the training examples to predict the correct label.
#### What is Reinforcment Learning and how would you define it?
        A learning differs from supervised learning in not needing labelled input/output pairs be presented, and in not needing sub-optimal actions to be explicitly corrected. Instead the focus is on finding a balance between exploration (of uncharted territory) and exploitation (of current knowledge) .Semisupervised learning is also known as Reinforcment learning, in reinforcment learning each learning steps involved a penalty criteria whether to give model positive points or negative points and based on that penalizing the model.
#### What is Deep Learning ?
        Deep learning is defined as algorithms inspired by the structure and function of the brain called artificial neural networks(ANN).Deep learning most probably focuses on Non Linear Analysis and is recommend for Non Linear problems regarding Artificial Intelligence.
#### Difference between Machine Learning and Deep Learning?	
        Since DL is a subset of ML and both being subset of AI.While basic machine learning models do become progressively better at whatever their function is, they still need some guidance. If an AI algorithm returns an inaccurate prediction, then an engineer has to step in and make adjustments. With a deep learning model, an algorithm can determine on its own if a prediction is accurate or not through its own neural network.
#### Difference between Bias and Variance?
        Bias is definned as over simpliciation assumption assumed by the model, while variance is definned as ability of a model to learn from Noise as 
        well
#### What is Linear Regressions ? How does it work?	
#### What is Logistic Regression? How does it work?	
#### What is Logit Function? or Sigmoid function/ where in ML and DL you can use it	
#### What is Support Vector Machine ? how is it different from  OVR classifiers?	
#### What is different type of Evauation metrics in Regression?
#### How would you define Mean absolute error vs Mean squared error?	
#### How would you evaluate your classifier?	
#### What is Classification? 	
#### How would you differentiate between Multilabel and MultiClass classification?	
#### Which Algorithms are High Biased Algorithms?	
#### Which Algorithms are High Variance Algorithms?	
#### Why are the above algorithms are High biased or high variance?	
#### What is Randomforest and Decision Trees?	
#### How does RandomForest Works and Decition Trees?	
#### What is Gini Index? Explain the concept?
        The Gini Index is calculated by subtracting the sum of the squared probabilities of each class from one. It favors larger partitions.
        Imagine, you want to draw a decision tree and wants to decide which feature/column you should use for your first split?, this is probably defined
        by your gini index.
#### What is the process of gini index calculation?
        Gini Index:
        for each branch in split:
            Calculate percent branch represents .Used for weighting
            for each class in branch:
                Calculate probability of class in the given branch.
                Square the class probability.
            Sum the squared class probabilities.
            Subtract the sum from 1. #This is the Ginin Index for branch
        Weight each branch based on the baseline probability.
        Sum the weighted gini index for each split.
#### What is the formulation of Gini Split / Gini Index?
        Favors larger partitions.
        Uses squared proportion of classes.
        Perfectly classified, Gini Index would be zero.
        Evenly distributed would be 1 – (1/# Classes).
        You want a variable split that has a low Gini Index.
        The algorithm works as 1 – ( P(class1)^2 + P(class2)^2 + … + P(classN)^2)
#### What is probability? How would you define Likelihood?	
#### What is Entropy? and Information Gain ? there difference ?
        Information Gain multiplies the probability of the class times the log (base=2) of that class probability.  Information Gain favors smaller partitions with many distinct values.  Ultimately, you have to experiment with your data and the splitting criterion.
#### How would you define ROC Curve?	
#### How would you define True positives and True Negatives?	
#### How would you define precision and Recall ?	
#### Which one would you prefer for you classification model Precision or Recall?	
#### What is F1 Score? which intution does it gives ?	
#### What is difference between Preceptron and SVM?	
#### What is the difference between Logsitic and Liner Regressions? 	
#### What are outliers and How would you remove them?	
#### What are different Technique of Sampling your data?	
#### Can you define the concept of Undersampling and Oversampling?	
#### What is SMOTE?	
#### How would you resolve Overfitting or Underfitting? 	
#### Mention some techniques which are to avoid Overfitting?	
#### What is a Neuron?	
#### What are Hidden Layers and INput Layers?	
#### What are Output Layers?	
#### What are activation functions ? 	
#### What is Convolotional Neural Network?	
#### What is recurrent Neural Network?	
#### What is Convolotional Layer?	
#### What is MaxPooling Layer? How does it work?	
#### What is Kernel or Filter?	
#### What is Activation functions?	
#### What is Segmentation?	
#### What is poster analysis?	
#### What is Forward propagation?	
#### What is backward propagation?	
#### what are dropout neurons?	
#### what are flattening layers?	
#### How is backward propagation dealing an improvment in the model?	
#### What is correlation? and covariance?	
#### What is Anova? when to use Anova?	
#### How would you define dimentionality reduction? why we use dimentionality reduction?	
#### What is Principle componenet analysis? how does PCA work in Dimentonality reduction?	
#### What is Maximum Likelihood estimation?	
#### Define process of Regularization? and how does it works?### 	
#### What is Naive Bayes? How does it works?	
#### What is KNN how does it works? what is neigbouring criteria? How you can change it ?	
#### What is Conditional Probability? what is distributive Probability?
#### How would you define Cross Entropy?
#### Which one would you prefer low FN or FP's based on Fraudial Transaction?
#### Differentiate between KNN and KMean?	
#### What is Attention ? Give Example ?	
#### What are AutoEncoders? and what are transformers?	
#### How would you define GAN(Generative Adversarial Networks) ?	
#### What are Gausian Processes?	
#### What is Graph Neural Network?	
#### Define Text Classification, Give some usecase examples?	
#### What is Language Modelling(LM), give examples?	
#### Define Named Entity recognition? Give some usecases where it can come in handy?	
#### What is Image Captioning?	
#### Give some example of Text summarization.	
#### Define Style Transfer?	
#### Define Image Segmentation and Pose Analysis?	
#### Define Semantic Segmentation?	
#### What is Instance Segmentation?	
#### What is Imperative and Symbolic Programming?	