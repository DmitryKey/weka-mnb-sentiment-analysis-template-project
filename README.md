weka-mnb-sentiment-analysis-template-project
============================================

The template project for three and five way sentiment classification.

If you are looking to integrate natural language processing APIs or modules into your projects, check this repo out: https://github.com/semanticanalyzer/nlproc_sdk_sample_code

The blog post describing this code in English: [http://dmitrykan.blogspot.com](http://dmitrykan.blogspot.fi/2014/04/weka-template-project-for-sentiment.html)
In Russian (блог-пост на русском): [http://habrahabr.ru/](http://habrahabr.ru/post/229779/)

In order to utilize the kaggle's training set the code is using you need to accept the terms and conditions of the
competition and put the training set train.csv into the kaggle directory.

The three way model trained using unigrams is as good as the following stats:

    Correctly Classified Instances       28625               83.3455 %
    Incorrectly Classified Instances      5720               16.6545 %
    Kappa statistic                          0.4643
    Mean absolute error                      0.2354
    Root mean squared error                  0.3555
    Relative absolute error                 71.991  %
    Root relative squared error             87.9228 %
    Coverage of cases (0.95 level)          97.7697 %
    Mean rel. region size (0.95 level)      83.3426 %
    Total Number of Instances            34345


The same training for five way model shows:

    Correctly Classified Instances      104814               67.1626 %
    Incorrectly Classified Instances     51246               32.8374 %
    Kappa statistic                          0.4883
    Mean absolute error                      0.1916
    Root mean squared error                  0.3111
    Relative absolute error                 72.6628 %
    Root relative squared error             85.6599 %
    Coverage of cases (0.95 level)          96.3732 %
    Mean rel. region size (0.95 level)      60.9708 %
    Total Number of Instances           156060


Feel free to fork and use the code the way you want. The license is ASL 2.0.
