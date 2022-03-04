# Machine-Learning-Project
machine learning task

## Objective
Algorithm built to learn and recognise pictures of flowers. The algorithm is given a dataset of 3670 photos of flowers and is aimed to class five different types of flowers: daisy, dandelion, roses, sunflower and tulips.

## Machine Learning
The computer can't collect and discover new knowledge by itself, it can only be conducted by existing truths. It can't discover new logical theories or new rules. It always need some knowledge to understnad the information from the given pictures, which the computer can use to learn new knowledge step by step. The learning process of the computer is an expansion and perfection of the knowledge base. This is why the data set is split into training and validation.


## Supervised Learning?
It is based off supervised learning as it pushes in well labelled test data and learns from it. The data set is split such that 80% of the images are used for training and 20% are used for validation. Five classes are created for each flower subcategory. What this means is that a a chunk of the data set is labelled and given to the computer so that it can pick up on common features of a certain class. For example: it may pick up on the fact that the colour red is associated with roses.
![Screen Shot 2022-03-03 at 11 05 38 PM](https://user-images.githubusercontent.com/99629733/156603463-8fce7527-4c9d-4a54-b6c6-0654a83ebfb1.png)

The training loss indicates how well the model is fitting the training data, while the validation loss indicates how well the model fits new data.




Below is a visual representation of an example in the way supervised learning works:
![Screen Shot 2022-03-03 at 10 57 43 PM](https://user-images.githubusercontent.com/99629733/156601925-3cd56a5c-9700-4e19-8c93-c1159375f7fc.png)

## Reinforcement Learning?

Reinforcement learning is when a machine learning model is given no hints on how to succesfully approach a task but depending on its actions it is either rewarded or punished, with it's goal being to maximise the reward. In the context of this model it is not used but it could be if a tracker for a reward was used. This would +1 to the reward for every value appropriately placed and -1 for every misplaced image. The algorithm would be set to try to maximise the reward and so it would try to avoid misplacing images.

![Screen Shot 2022-03-03 at 11 21 26 PM](https://user-images.githubusercontent.com/99629733/156606501-28dc72c2-70ec-4654-a29d-701feb1aa64d.png)

A good implementation of reinforcement learning could be through Q learning in which a table is initialised and is updated in depending on how the agent acts within the environment. The table contains actions and outcomes from which the agent will try to exploit to avail the maximum reward in a given state. 

## Classification Model

The model of the program is a classification model as its objective is to divide the data into a groups such that data points in the same group are similar to pre-existing values. In other words, data with similar traits are sorted into groups where the original data matches the new data.


## Regression Model
The regression model wouldn't fit this particular model because it is used for continuous values such as price or length. Placing a flower into a set of five can't be shown using a regression model graph.

![Screen Shot 2022-03-04 at 6 05 44 AM](https://user-images.githubusercontent.com/99629733/156667840-a6a52122-95f2-4cd4-9ad3-d1eabaa783de.png)

It graphs out a continuous value to try and predict the line for unknown values.

## Clustering Model
The clustering model could fit this model had the data not been split up into validation and training. Since the clustering model is a form of unsupervised learning, it isn't given pre-labelled data, rather it has to cluster similar data together. 

It can be visually represented by sets:

![Screen Shot 2022-03-04 at 6 11 53 AM](https://user-images.githubusercontent.com/99629733/156668548-a33071a6-84ed-44c9-aab2-01f2f70dd83d.png)

In this example the five subcategories would be the five types of flowers.

## Deep Learning
This program is a form of deep learning since it makes use of a neural network with more than three layers.

![Screen Shot 2022-03-04 at 6 15 52 AM](https://user-images.githubusercontent.com/99629733/156669034-a1966089-812f-41bc-8dc5-9fe346d508a2.png)


Representation of a neural network:

![Screen Shot 2022-03-04 at 6 16 36 AM](https://user-images.githubusercontent.com/99629733/156669123-417ce894-b6c6-4aa8-a63e-cf503c95c960.png)

A neural network is a series of algorithms that are utilised to recognise the relations between given data through a process that mimics the way the human brain works. 


## Back-propagation
A way of propagating the total loss back into the neural network to know how much of the loss every node is responsible for. From this the responsible node can be amended. This program uses a loss function to implement this.

Before Back-Propagation:
![Screen Shot 2022-03-04 at 7 59 21 AM](https://user-images.githubusercontent.com/99629733/156678907-8527626c-8a20-420c-9259-7ac5b864baf9.png)

After Back-Propoagation:
![Screen Shot 2022-03-04 at 6 54 26 AM](https://user-images.githubusercontent.com/99629733/156672955-23c618d2-91e9-4f94-be2d-192d9bacec33.png)
