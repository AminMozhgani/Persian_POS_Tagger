# Persian_POS_Tagger

```
#این عضو شورای نگهبان تایید کرد در صورتی که چند تن از نمایندگان تهران حذف شوند انتخابات باید در مرحله دوم برگزار شود .

عضو/NOUN
شورای/NOUN
نگهبان/NOUN
تایید/NOUN
کرد/VERB
در/ADP
صورتی/NOUN
که/CCONJ
چند/ADJ
تن/NOUN
از/ADP
نمایندگان/NOUN
تهران/NOUN
حذف/NOUN
شوند/AUX
انتخابات/NOUN
باید/AUX
در/ADP
مرحله/NOUN
دوم/ADJ
برگزار/ADJ
شود/AUX
./PUNCT
```


It's a Persian POS Tagger trained by [The Persian Universal Dependency Treebank (Persian UD)](https://github.com/UniversalDependencies/UD_Persian) with Tensorflow.
I've used [TensorFlow Part-of-Speech Tagger](https://github.com/mrahtz/tensorflow-pos-tagger) codes for this purpose.
The training set shows **90%** accuracy over **13800** steps of training with **0.5** loss.

## Using

Just put your text in **data/input.txt** file and execute **python demo.py**, the desired result will be added to **data/result.txt**.
