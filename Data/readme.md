# Metrics & Methods

## Metrics we Measured
1) Lexical Entropy
2) Sentence Length Deviation (Burstiness)
3) Most Frequently Used Words (Burrow's Delta)
4) Character N-Grams
5) POS N-Grams
6) Punctuation

## Methods
1) **Support Vector Machine**
We trained a Support Vector Machine on human texts and tested them on each AI text. We checked to see which one of the fourteen classes the AI texts fell into and measured the F1 & Accuracy Score.
(To check whether or not the SVM was able to put an imitated AI text into the class with the author it imitated)

2. **Cluster Diagrams**
While the SVM was forced to choose one of the 14 human author classes for the AI texts, a cluster diagram measured whether an AI text was clearly different from the human texts.
(2 clusters, Human + AI)
For all 3 generations we noticed that at 300MFW, AI texts were classified seperately from humans, indicating that AI contains a distinct style.

3. **Bar Graphs**
To show differences in punctuation, lexical entropy and sentence length deviation to better understand how AI differs from human writing.







