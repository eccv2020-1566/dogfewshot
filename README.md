# On the texture bias for Few-Shot CNN segmentation
ECCV Submision Paper ID: 1566
</br>

# Run Demo
1- Download the FSS1000 dataset from [this](https://drive.google.com/open?id=16TgqOeI_0P41Eh3jWQlxlRXG9KIqtMgI) link and extract the dataset.</br>
2- Run `Train_DOGLSTM.py` for training Scale Space Encoder model using k-shot episodic training.</br>
3- Run `Train_weak.py` for training Scale Space Encoder model using k-shot episodic training and evaluatign on the weak annotation test set. This code will use weaklly annotated bouning box as a label for the support set on test time.

