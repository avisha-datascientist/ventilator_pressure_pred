# GI Tract Image Segmentation

![Scans]()
- **General Information and Goal:**
  What are MRI scans?
Magnetic resonance imaging (MRI) is a type of scan that uses strong magnetic fields and radio waves to produce detailed images of the inside of the body. An MRI scanner is a large tube that contains powerful magnets. You lie inside the tube during the scan.
The class widthin the train.csv file has 3 distinct values: large bowel, small bowel, stomach. These are all part of the digestive system. The bowels (small and large intestine) are responsible for breaking down food and absorbing the nutrients.
- **Dataset:** [GI Tract Segmentation Dataset](https://www.kaggle.com/competitions/uw-madison-gi-tract-image-segmentation/data)
- **Type of Task:** The training annotations presented as RLE-encoded masks in 16-bit grayscale PNG format. Cases in the competition consist of multiple sets of scan slices identified by the day of the scan, with some cases split by time (train/test) and others by the entirety of the case. The objective is to generalize to both partially and wholly unseen cases, with the test set comprising roughly 50 entirely unseen cases, each varying in the number of days and slices, similar to the training set.
- **The Notebook:** In the notebook, I begin with data loading, conversion, visualization and analysis of the 16 bit masks.







