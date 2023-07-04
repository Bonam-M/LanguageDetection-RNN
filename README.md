# LanguageDetection-RNN
This is a basic Natural Language Processing (NLP) project to detect the Language of a name via Multiclass text classification using characters.

## How does it work?
Below is a description of the process used.

#### Load the labeled data
Make sure the data in a the proper fromat: text files containing names in different languages

#### Define and populate the vocabulary of the project
Create a dictionary all the names in a specific languages and a list of all the languages we have in our dataset. Here are the languages we have:
``` 
[
    'Arabic', 'Chinese', 'Czech', 'Dutch', 'English', 'French', 'German',
    'Greek', 'Irish', 'Italian', 'Japanese', 'Korean', 'Polish', 'Portuguese',
    'Russian', 'Scottish', 'Spanish', 'Vietnamese'
 ]

```

#### Preprocess the data
Convert every letter or character in a name to its one-hot encoder equivalent. Then, transform each indivual name in the dataset to its tensor format.

#### Designing the Recurrent Neural Network (RNN)
The RNN helps to classify the names in specific categories, in this case the categories are the languages in the vocabulary of our projects.

#### Train and Test the RNN model
Parse every character in our input name into the RNN.
Then, train the model on 20 000 names while keeping track of the current loss and all of the losses during the training process. To test the model, we simply get the top 3 predictions from the model and compare them with the actual language labels.


## What can you find in this repo?
Here is a description of the content of this repository.

#### Notebook containing the full step by step process
The Notebook has all the instructions on the packages required to run the experiment and test the model on your local machine.

#### Datasets
You'll find all the text files used to train the model under the _data_ folder.

## Happy ML coding
Keep learning and pushing the boundaries of technology!
