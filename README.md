# Musk_Non-Musk

The dataset contains details about organic chemical compounds including their chemical features, isomeric conformation, names and the classes in which they are classified.

I have first performed a multiclass classification of all forms of molecules present, i.e, 102, under 'molecule_name'. This achieved 96% accuracy. (Suggested by: https://github.com/rani700/molecules_classification )

I then performed the required binary classification of 'Musk or Non_Musk' molecules. This achieved 99% accuracy.


#Dataset Information:

( https://archive.ics.uci.edu/ml/datasets/Musk+(Version+2) )
This dataset describes a set of 102 molecules of which 39 are judged by human experts to be musks and the remaining 63 molecules are judged to be non-musks. The goal is to learn to predict whether new molecules will be musks or non-musks. However, the 166 features that describe these molecules depend upon the exact shape, or conformation, of the molecule. Because bonds can rotate, a single molecule can adopt many different shapes. To generate this data set, all the low-energy conformations of the molecules were generated to produce 6,598 conformations. Then, a feature vector was extracted that describes each conformation.

This many-to-one relationship between feature vectors and molecules is called the "multiple instance problem". When learning a classifier for this data, the classifier should classify a molecule as "musk" if ANY of its conformations is classified as a musk. A molecule should be classified as "non-musk" if NONE of its conformations is classified as a musk.



