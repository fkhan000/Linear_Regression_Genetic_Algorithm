# Linear_Regression_Genetic_Algorithm



In this project, I wanted to evaluate the performance of a linear regression model whose weights were chosen by a genetic algorithm. Specifically I wanted
to see two things: the GA regression model having an easier time generalizing on the testing set and significantly outperform the linear regression model
when there is a very small amount of training data available. In the graph below, the performance of the GA and linear regression model was plotted as a
function of the amount of the data the models were allowed to train on. And as can be seen, the GA regression model 
consistently outperforms the linear regression model even when there is very little training data. However, what's amazing and also confusing is that
the linear regression model performs nearly just as well with 80% of the training data as it does with just 5%. It's possible that the dataset that I used,
the california housing dataset, is too simple and so the model doesn't need that much data to figure out the relationships between the labels and the
features. Unfortunately, because of this, I can't be certain that the GA regression model performs better than the linear regression model
when there's very little data available. I first need to find a harder dataset. 
