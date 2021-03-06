# Matt_Portfolio
My Programming and Data Science Portfolio

## Data Science and Statistics

### [Project 1: NCAA Unbiased Rankings](https://github.com/mattgevercer/Computing-and-Machine-Learning-for-Economics/tree/main/ColleyRank)
* Adapted Colley's unbiased method for ranking college football teams into python code using two different algorithms.
* Wrote python code that scrapes historical NCAA football data from the web. 
* [Click here for full description of the Colley Method](https://www.colleyrankings.com/matrate.pdf)

### [Project 2: World Bank Data Scraper](https://github.com/mattgevercer/Computing-and-Machine-Learning-for-Economics/tree/main/World_Bank_Import)
* Scrapes data for any given economic indicator from any given year on the World Bank website.
* Parses the website's HTML using Beautiful Soup and outputs the data in a pandas DataFrame. 
* [Click here for descriptions of World Bank indicators](https://data.worldbank.org/indicator)

## Machine Learning and Deep Learning

### [Project 3: Classifying American Sign Language Letters](https://github.com/mattgevercer/ASL_Classifier)
* Constructs a neural network for classifying pictures of American Sign Language letters. 
* Achieves around 93% accuracy in classifying images in a validation dataset. 
* Visualizes training loss versus validation loss as training progresses to gauge overfitting in the model. 
* [Click here for dataset documentation](https://www.kaggle.com/datamunge/sign-language-mnist)

![ASL_Train](images/ASL_Train.png) ![ASL_AC](images/ASL_AC.png)

### [Project 4: Classifying Handwritten Digits](https://github.com/mattgevercer/Digit-Recognition)
* A computer vision program that shows the difference in accuracy for guessing handwritten digits between a regular dense neural network and a convolutional dense neural network. 
* Achieved over 98% accuracy in classifying handwritten digits.
* Visualizes how accuracy of predicting validation data improves as training progresses. 
* [Click here for dataset documentation](http://yann.lecun.com/exdb/mnist/)

![Digit Image](./images/Digits%20Figure.png?raw=true)

### [Project 5: Predicting House Prices](https://github.com/mattgevercer/Computing-and-Machine-Learning-for-Economics/tree/main/Model_Selection)
* Implements k-fold cross-validation in scikit-learn. 
* Implements two algorithms for finding the best subset of linear predictors for a dependent variable. 
* Tests the subsetting algorithms by building a linear model to predict house prices in California. 
* [Click here for dataset documentation](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html)

## Reinforcement Learning

### [Project 6: The Prisoner's Dilemma](https://github.com/mattgevercer/Prisoners_Dilemma)
* Creates a simple reinforcement learning environment (adapted from Open AI's gym) to simulate the Prisoner's Dilemma.
* Simulates the Prisoner's Dilemma game between two epsilon-decreasing agents over 1000 Monte Carlo episodes. 
* Tracks learning progess with a barplot and shows convergence towards a mutual defection strategy.
* [Click here for more information on the Prisoner's Dilemma](https://www.investopedia.com/terms/p/prisoners-dilemma.asp)

![Payoffs](images/Payoffs.png) ![PD_plot](images/PD_plot.png) 

### [Project 7: Cliff Walking](https://github.com/mattgevercer/Cliff_Walking)
* Uses an enviroment programmed with OpenAI's gym library to simulate the Sutton and Barto Cliff Walking problem.
* Utilizes a temporal difference learning method. 
* Experiments with epsilon-greedy and epsilon-decreasing strategies.
* Achieves an overall win rate of 51.88% after 10,000 epsiodes. 
* [Click here for more information on the Cliff Walking environment](https://github.com/caburu/gym-cliffwalking)

![cliff_walking](images/cliff_walking.png) ![CW_plot](images/CW Bar Plot.png) 

## Games and Puzzles

### [Project 8: Letter Boxed Solver](https://github.com/mattgevercer/Letter_Boxed_Solver)
* Allows for user input of any 3-by-3 New York Times Letter Boxed puzzle.
* Applies the Letter Boxed rules to subset a list of English words using combinatoric functions. 
* Solves the puzzle with the shortest possible number of words.
* [Click here to play Letter Boxed](https://www.nytimes.com/puzzles/letter-boxed)

### [Project 9: Six Degrees of Kevin Bacon](https://github.com/mattgevercer/Degrees)
* Finds the shortest path between any two actors using a breadth-first search algorithm. 
* Returns the "path" (i.e. the films where two connected actors appeared with eachother). 
* Returns the "steps" in the path (i.e. the number of degrees between the two actors). 
* [Click here for in-depth project description](https//cs50.harvard.edu/ai/2020/projects/0/degrees/)
