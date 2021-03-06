# STANetASAL
 ## **Extracting features (hand-craft vs automatic extracting)**

Okay, this a can be a large topic in machine learning that needs an entire book to discuss. Typically described in the context of a topic called *feature engineering.* In this section we’re only concerned with extracting features in images. I’m going to touch on the idea quickly.

## **Traditional machine learning uses hand-crafted features**

In traditional machine learning problems, we spend a good amount of time in **manual** features selection and engineering. In this process we rely on our domain knowledge (or partnering with domain experts) to create features which make machine learning algorithms work better. We then feed the produced features to a classifier like Support Vector Machines (SVM) or Adaboost to predict the output. Some of the handcrafted feature sets are:

- Histogram of Oriented Gradients (HOG)
- Haar Cascades
- Scale-Invariant Feature Transform (SIFT)
- Speeded Up Robust Feature (SURF)

## **Deep learning automatically extracts features**

In deep learning, we don’t need to manually extract features from the image. The network **automatically** extracts features and learns their importance on the output by applying weights to its connections. You feed the raw image to the network and, as it passes through the network layers, it identifies patterns within the image to create features. Neural networks can be thought of as feature extractors + classifiers which are end-to-end trainable as opposed to traditional ML models that use hand-crafted features.
