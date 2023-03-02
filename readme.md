# Take Home

https://fetch-hiring.s3.us-east-1.amazonaws.com/data-scientist/deep-learning/deep_learning_take_home.html

Your solution may include any or all of the following:

1. Profile the node attributes and discuss what embeddings they suggest
    
    These are the baseline attributes 

    attribute 0: 9 distinct values
        [0.0, 1.0, 3.0, 5.0, 17.0, 21.0, 34.0, 40.0, 48.0]
    attribute 1: 14 distinct values
        [0.0, 3.0, 11.0, 13.0, 17.0, 29.0, 30.0, 42.0, 44.0, 45.0, 47.0, 48.0, 52.0, 54.0]
    attribute 2: 9 distinct values
        [0.0, 1.0, 3.0, 5.0, 17.0, 21.0, 34.0, 40.0, 48.0]
    attribute 3: 14 distinct values
        [0.0, 3.0, 11.0, 13.0, 17.0, 29.0, 30.0, 42.0, 44.0, 45.0, 47.0, 48.0, 52.0, 54.0]

    They might represent actions, and 0-1-2-3 is a sequence of actions, e.g. actions performed on page1, page2, page3 and then page4. Not sure. There are too many possibilities.

2. Select a framework

    Polars will work for the algorithms I want to use. No need for graph packages.

3. Select one or more standard classification algorithm(s) for the problem and explain your choice(s)

    See documentation.

4. Write your own classification algorithm

    See idea 1.

5. Write a training routine to arrive at your best model for this data

    No time to fine-tune. Whatever.

6. Discuss how you tuned the model, including selection of hyperparameters, loss, and activation functions

    No time to fine-tune. Whatever.

7. Predict how your model will perform on unseen data

    I think idea 1 will be quite stable because it does not require any training and will yield consistent performance. Other ML approaches might yield better results given more data. 

    Hm....
    



