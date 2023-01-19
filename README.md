# ACM Research coding challenge (Spring 2023)

![image](https://user-images.githubusercontent.com/72369124/211179527-0ee60624-2794-4e13-bf7f-f88b5c950e44.png)

This semester's challenge is especially open-ended.  on Kaggle called "Star dataset to predict star types".  

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

## INSTRUCTIONS: Please read this carefully, do not skim this!

### Here's the coding challenge: **What can you do with all of this data?** Yes, this is an **OPEN-ENDED** question and your answer should be a brief report, showcasing your skills. Can you find a pattern, answer a question, or create a visualization? In case nothing comes to mind, here are some ideas, with varying complexity:

- What is the most common star type in the data?
- What common patterns do you notice between any two properties? Ex: Is there a relationship between the star color and temperature?
- What properties are the most influential in classifying a star's type?
- Can you make a similar graph as the one shown in Kaggle to showcase the data as a Hertzsprung-Russell Diagram?
- Train a machine learning model to then predict the star type of a row of data (without the star type field) and find the model's accuracy.
Bonus: Can you find the row of data that most closely resembles our star, the Sun?

However, we strongly encourage you to come up with your own problem to solve! This is for you to showcase your skills!



3. Replace this README file with a description ([written in Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/about-writing-and-formatting-on-github)) of your solution. Regardless of your success, describe the problem you set out to solve and how you did it. Split it up into sections with headers, and, if relevant, include figures.


5. Make sure your GitHub repo has everything important, including your report, any code you used, graphs, etc. You should not be working on this after the deadline (Feb 2).

## Language and Frameworks used
Python: pandas, numpy, sklearn, seaborn
These frameworks were used to statistically and graphically explore the dataset, as well as train the data.

## Problems set out to solve
The problems I set out to solve: 
- What is the most common star type?
- How do each star type compare to each other in terms of temperature, radius and luminmosity?
- Is there a machine learning model that can accurately identify what is a dwarf planet and what is not using temperature and luminosity as factors?
I also trained a logistic regression model on the dataset to see how accurately it can predict star types (can the model accurately identify what is a dwarf planet and what is not using temperature and luminosity as factors?).

## What was learned
- There was no singular, common star type within this dataset, but rather an equal number of each
- The logistic regression model had a 0.96 accuracy score in predicting the different stars, making it a suitable model to train this dataset

## Links referenced
- [My previous ML exploration projects](https://github.com/haniyyahh/ML-Portfolio)

--------------------------------------------------------------------------------------
## No collaboration policy

**You may not collaborate with anyone on this challenge.** You _are_ allowed (and encouraged) to use internet documentation. If you use existing code (either from Github, Stack Overflow, or other sources), **please cite your sources in the README**.

