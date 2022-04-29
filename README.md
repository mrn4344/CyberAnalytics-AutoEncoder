# CyberAnalytics-AutoEncoder

In this repo, there is two folders: 2018_Train and 2017_Test.

---
## 2018_Train

In this file, the code is setup to train on CIC-IDS-2018 day 2 (2/15).

This code will then test/measure the separation on day 1 (2/14).

Finally, this notebook will save two files: 2018_model.pth, and normalization.data.

### 2018_model.pth

- This file stores the trained model.

### normalization.data

- This file stores the data needed to normalize the data the same way from 2018 to 2017.

---
## 2017_Test

This folder contains a day's CSV from CIC-IDS-2017, and the jupyter notebook in there is setup to load the model and normalization data from the 2018 model, then test the separation between benign and DDoS in the 2017 dataset.

***COPY THE TWO OUTPUT FILES FROM THE 2018 FOLDER TO THE 2017 FOLDER***

At the end of the notebook, the separation measured as well as a histogram will be shown.

---
## Notes
You might need some libraries like torch and qqdm. These should be able to be pip installed. If everything goes right, you should be able to just hit 'run all' on each notebook.
