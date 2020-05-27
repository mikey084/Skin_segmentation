# Skin_segmentation
Classification analysis for UCI Skin Segmentation Dataset

For the final project of EE257, I have worked on building data models to evaluate the Skin Segmentation dataset from the University of California Irvine database. The following is a breakdown of our analysis.
Dataset description 
Dataset Cleaning
Feature Extraction
4 model fit
Fine Tune Model
Performance Measurement

# Dataset Description

The important column of this dataset is skin_nonskin, this column is responsible for classification of an observation if it is skin type or not. This dataset also includes three columns of red, blue, green, values that are associated with face colors of different demographics. These demographics include range of age (young, middle-aged, old), race ethnicity (white, asian, black), and gender (male, female). RGB values refers to a system for representing colors to be used on a computer display. The colors are attributed to integer values respectively. These RGB values can be combined in various proportions to obtain any color in the visible spectrum. Thus this system is very useful in interpreting skin or non skin types in image analysis.
These facial images are obtained from the FERET and PAL database. The dataset is of dimensions 245057 * 4 where the first three columns are blue, green, red(x1, x2, x3 features), and fourth column is of skin or nonskin(decision variable y). 

