This notebook will guide you through smaller portions of your final project. For this notebook, we will be using the Abalone dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Abalone) (originating from the Marine Research Laboratories – Taroona). This dataset should already be in your folder (under `abalone.csv`) or you can download it at the above link. 

![Abalone](https://github.com/Batserine/Predictive_Analytics/blob/master/Data%20processing%20and%20Visualization/BDPV%20-%20Mini%20Project/abalone.jpg)

### A Brief History of Abalones

An abalone is a sea snail belonging to one of a range of 30 to 130 species (depending on which scientist you ask). It is commonly prized for its mother-of-pearl shell, pearls, and delicious flesh by a variety of cultures and has long been a valuable source of food in its native environments. Sadly, wild populations of abalone have been overfished and poached to the point where commercial farming supplies most of abalone flesh nowadays. It now sits on the list of current animals threatened by extinction.

Source: https://en.wikipedia.org/wiki/Abalone

## Dataset

The purpose of this dataset is to predict the age of an abalone through physical characteristics, determined by cutting the shell through the cone, staining it, and counting the number of rings through a microscope -- a boring and time-consuming task. Good thing it's already been done for us!

Below is the dataset description from the UCI Machine Learning Repository. 

|Name	|	Data Type|	Measure	|Description|
|	----	|	---------|	-----	|-----------|
|	Sex		|nominal		|	|M, F, and I (infant)|
|	Length	|	continuous	|mm|	Longest shell measurement|
|	Diameter	|continuous|	mm	|perpendicular to length|
|	Height	|	continuous	|mm	|with meat in shell|
|	Whole weight|	continuous	|grams	|whole abalone|
|	Shucked weight	|continuous|	grams	|weight of meat|
|	Viscera weight	|continuous|	grams	|gut weight (after bleeding)|
|	Shell weight	|continuous|	grams	|after being dried|
|	Rings	|	integer		|	|+1.5 gives the age in years|

Run the cells below to examine the dataset. 
