# On the texture bias for Few-Shot CNN segmentation
ECCV Submision Paper ID: 1566
</br>

# Run Demo
1- Download the FSS1000 dataset from [this](https://drive.google.com/open?id=16TgqOeI_0P41Eh3jWQlxlRXG9KIqtMgI) link and extract the dataset.</br>
2- Run `Train_DOGLSTM.py` for training Scale Space Encoder model using k-shot episodic training.</br>
3- Run `Train_weak.py` for training Scale Space Encoder model using k-shot episodic training and evaluatign on the weak annotation test set. This code will use weaklly annotated bouning box as a label for the support set on test time.

# FSS1000 Data set bounding box annotation provided [Download link](https://github.com/eccv2020-1566/dogfewshot/raw/master/FSS-1000%20Bounding%20Box%20Annotation.zip)
![Bounding Box annotation for FSS-1000](https://github.com/eccv2020-1566/dogfewshot/blob/master/Weak%20Annotation%20samples%20for%20FSS1000.jpg)
