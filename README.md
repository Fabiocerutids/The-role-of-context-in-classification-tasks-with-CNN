# The-role-of-context-in-classification-tasks-with-CNN
GitHub repo investigating how mimicking human contextual understanding can enhance CNNs in object classification. Uses iNaturalist dataset to study context's impact on CNN performance. 

We have divided our notebooks in folders:

1. Deep_Learning_model: this directory contains all of the codes and architectures we used to run our deep learning models. Some files contains code that is very similar except fro the type of pictures and sizes of imaged used. We nevertheless decided to include them to give a comprehensive overview of our work.

2. Error_analysis: This section contains notebooks that we used to run all our exploratory analyses on the dataset and on the test results. In contains also the code used to extract features later used in the login models, bootstrap analysis and overall model accuracy considerations.

3. Utility_notebooks: This directory presents series of notebooks that outline specific tasks that we carried out throughout the analysis. We have the code that we used to extract bonding boxes and mask the animals, together with the code used to reverse the CLIP model and smooth the bonding boxes.

4.Clustering_analysis: This folder contains all of the clustering analysis we ran on the data, both as an exploratory tool and as an inferential one. Also here we have some notebooks that present similar code if not for the data used.

5. test_results: This directory contains a series of pickle files that once opened give access to a data frame with the predicted labels for each of the test picture form each model. For example: transfer_bbcontent_testresults.pickle contains the label predicted on the test images by the model trained on only the content of the bonding boxes.
