# Persian_POS_Tagger

It's a Persian POS Tagger trained by [The Persian Universal Dependency Treebank (Persian UD)](https://github.com/UniversalDependencies/UD_Persian) with Tensorflow.
I've used [TensorFlow Part-of-Speech Tagger](https://github.com/mrahtz/tensorflow-pos-tagger) codes for this purpose.
The training set shows **90%** accuracy over **13800** steps of training with **0.5** loss.

## Using

Just put your text in **data/input.txt** file and execute **python evaluate.py**, the desired result will be added to **data/result.txt**.
