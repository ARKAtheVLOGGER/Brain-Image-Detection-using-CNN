**Introduction:** In modern days, checking the huge number of MRI (magnetic resonance imaging) images
and finding a brain tumour manually by a human is a very tedious and inaccurate task. It can affect the
proper medical treatment of the patient. Again, it can be a hugely time-consuming task as it involves
a huge number of image datasets. There is a good similarity between normal tissue and brain tumour
cells in appearance, so segmentation of tumour regions become a difficult task to do. So there is an
essentiality for a highly accurate automatic tumour detection method.

**Method:** In this paper, we proposed an algorithm to segment brain tumours from 2D Magnetic Resonance
brain Images (MRI) by a convolutional neural network which is followed by traditional classifiers and
deep learning methods. We have taken various MRI images with diverse Tumour sizes, locations, shapes,
and different image intensities to train the model well. Furthermore, we have applied SVM classifier and
other activation algorithms (softmax, RMSProp, sigmoid, etc) to cross-check our work. We implement our
proposed method using “TensorFlow” and “Keras” in “Python” as it is an efficient programming language
to perform fast work.

**Result:** In our work, CNN gained an accuracy of 99.74%, which is better than the state of the result
obtained so far.

**Conclusion:** Our CNN based model will help the doctors to detect brain tumours in MRI images
accurately, so that the speed in treatment will increase a lot.
