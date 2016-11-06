# mlsec
Various projects related to Machine Learning and security data

## CSIC classifiers
The two python notebooks show different classifiers trained on the CSIC 2010 full dataset obtained from here: http://users.aber.ac.uk/pds7/csic_dataset/csic2010http.html

The dataset contains http requests labelled as *norm* or *anom*. At the moment, the classifiers only take into account the *payload* data and they are not tuned. A fully connected neural network using keras is included in the CSIC_keras notebook.
