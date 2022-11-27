# Language-Detection
This Language detection model has been developed b Pranav using Python. This model uses Multinomial naives bayes as it performs well in multi classifier.  There is 21 languages trained in this model.

# Pre-Requisites
You require pandas, numpy and sci-kit learn to run this python code.

# Installation
```
pip install pandas
pip install numpy
pip install sklearn
```
This is it for the installation process of the required libraries and modules.

# Dataset Used
You can find the used dataset from https://raw.githubusercontent.com/amankharwal/Website-data/master/dataset.csv
According to the code written you can access the dataset without actually installing it.
And about the Dataset, you can find around 21 languages with 1000 words each. This is a basic dataset and pretty much enough for training our model.

# Algorithm-Used
I have used Multinomial Naive Bayes as it performs well in multi-classifier models.

# Breakdown of Code
First tings first, I will be importing the required libraries and load in the dataset.
Then I will be sliptting the dataset with the required features and labels.

Here 'Text' will be my feature as we input it and 'language' will be  my label as we attemp to predict it.
Then using CountVectorizer I transform my text data into a matrix.
After this, I define my X_train, X_test, y_train, y_test using train test split.
I also declare test_size to 0.33 and random_state as 42.
Next, I will be implementing my Naive Bayes classifier and then I shall receive the input from User.
Now that we have the user_input, I will be using the user_input to predict the 'language' and print it out.

I will be uploading a video on this simple language detector on my Youtube Channel https://www.youtube.com/channel/UCRnsqre6S8SnQh7Jor3-tnQ.
Stay Tuned!

# Output
![Screenshot 2022-11-27 185954](https://user-images.githubusercontent.com/116950535/204138053-a6132b25-1601-4fa7-8770-c3f08df4920c.png)
So, this is something how the output looks like

# Verdict
Feel free to provide improvements to my code!!!
Thank You!
