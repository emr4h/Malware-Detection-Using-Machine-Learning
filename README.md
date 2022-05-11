# Malware-Detection-Using-Machine-Learning

<!-- ABOUT THE PROJECT -->
## About The Project

* This project analyzes PE information of exe files to detect malware.  
* In this repository you will learn how to create your own dataset and will be able to see the use of machine learning models using the dataset.  
* We will use machine learning for detect malware.


## Getting Started
This pe information was extracted using pefile.

If you want to create your own dataset, check out ```Data_Set_Generator.ipynb```

or you can use ```data-set/MalwareDataSet.csv```

## Dataset 

This dataset (MalwareDataSet.csv) contains a total of ```137,444 data```. 
There are ```96,526 safe and 40,918 malware```.

It has a total of 9 columns. The information of these columns is as follows:
```
* AddressOfEntryPoint
* MajorLinkerVersion
* MajorImageVersion
* MajorOperatingSystemVersion
* DllCharacteristics
* SizeOfStackReserve
* NumberOfSections
* ResourceSize
* legitimate
```


## Classification

We used 3 different classification algorithms. These :
```
* K Nearest Neighbors (KNN)
* Decision Tree
* Random Forest
```


## Results
```
The Success Rate was calculated as % 97.56118855679404 with the K-Nearest-Neighbors

The Success Rate was calculated as % 98.59433660254359 with the Decision Tree

The Success Rate was calculated as % 99.1240068682518 with the Random Forest
```




