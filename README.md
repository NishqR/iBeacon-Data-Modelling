# iBeacon Data Modelling
 
This repository includes an analysis, exploration and classification of the iBeacon Data that was made available here: https://archive.ics.uci.edu/ml/datasets/BLE+RSSI+Dataset+for+Indoor+localization+and+Navigation

The main task was to classify the location of certain coordinates on the map based on it's iBeacon readings. The data was preprocessed, explored with heatmaps to determine each beacon's strength and range. Two classifiers were then initialized, trained, and optimized for the purpose of classification - K-Nearest Neighbour Classifer and Decision Tree Classifier. Results were compared and determined to pick the best classifier for this task, more details on the same as well as the methodology and analysis can be found in report.pdf (can be opened in github itself)

The jupyter notebook, ibeacon_notebook.ipynb contains all the project code, with exploratory graphs, heatmaps, the entire Decision Tree, and even a way to test the classification of different locations within the notebook itself. You can run all the cells without any problems, as long as the necessary libraries are installed (you can check if you have all by just running the first cell). The notebook opens in github itself, if you just want to have a look. Here's a couple of screenshots from the jupyter notebook

## Heatmaps
![Sample Run](/images/heatmaps.jpg)

## Bubble Chart
![Sample Run](/images/bubble_chart.jpg)

## Decision Tree
![Sample Run](/images/decision_tree.jpg)
