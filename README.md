# ACM Research coding challenge (Spring 2023)

![image](https://user-images.githubusercontent.com/72369124/211179527-0ee60624-2794-4e13-bf7f-f88b5c950e44.png)

## Dataset used
["Star dataset to predict star types"](https://www.kaggle.com/datasets/deepu1109/star-dataset) from Kaggle.
It contains information about 240 stars and various properties taken from "Stars and Galaxies" by Seeds and Backman. Each row contains 7 pieces of information about a star, such as its temperature, luminosity, radius, absolute magnitude, star type, star color, and spectral class.

Please note that the star type, denoted as integers, are translated as the following:
- Brown Dwarf -> Star Type = 0
- Red Dwarf -> Star Type = 1
- White Dwarf -> Star Type = 2
- Main Sequence -> Star Type = 3
- Supergiant -> Star Type = 4
- Hypergiant -> Star Type = 5

---

## Language and Frameworks used
Python: pandas, numpy, sklearn, seaborn
These frameworks were used to statistically and graphically explore the dataset, as well as train the data.

## Problems set out to solve
The problems I set out to solve: 
- What is the most common star type?
- How do each star type compare to each other in terms of temperature, radius and luminosity?
- Is there a machine learning model that can accurately identify what is a dwarf planet and what is not using temperature and luminosity as factors?
I also trained a logistic regression model on the dataset to see how accurately it can predict star types (can the model accurately identify what is a dwarf planet and what is not using temperature and luminosity as factors?).

## What was learned
- There was no singular, common star type within this dataset, but rather an equal number of each
- ![image](https://user-images.githubusercontent.com/96028048/213610095-2dab6528-053b-42ec-8c44-ff856839efbc.png)
- ![image](https://user-images.githubusercontent.com/96028048/213610124-a1a0f0ab-796d-4d8a-8cc4-41be49f2abb2.png)
- ![image](https://user-images.githubusercontent.com/96028048/213610183-8b475bbf-f35e-46fd-b9a1-6dc666f4f342.png)
- The graphs above were plotted using seaborn, and highlight the differences amongst all star types in terms of mean temperature, radius and luminosity. Hypergiant stars had the highest mean radius and luminosity, while the main sequence stars had the highest mean temperature
- The logistic regression model had a 0.96 accuracy score in predicting the different stars, making it a suitable model to train this dataset

## Links referenced
- [My previous ML exploration projects](https://github.com/haniyyahh/ML-Portfolio)




