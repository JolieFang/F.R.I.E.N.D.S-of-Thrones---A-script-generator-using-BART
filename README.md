# F.R.I.E.N.D.S of Thrones - A script generator using BART
### (A group project for Natural Language Processing Class)

# Goal of this project

The main objective task of our project is text prediction. We create a model to check if it can come up with
creative ideas for a whole new story by using the script data that we train it on. Through self-supervised
tasks, our model will present the words with the highest probability following the initial input. We aim to have
a model able to write one single conversation between two characters, such as:

“Chandler Bing and Tyrion Lannister enter Central Perk and order a pint of ale.” – What do you imagine this
conversation to go like? How would Tyrion’s incessant wit deal with Chandler’s constant sarcasm? Sounds
like quite an intriguing situation, doesn’t it? It’s hard to imagine even for us as humans, but if we had to train
a machine to come up with this conversation, what might that look like?

#  DATA
- The data used comprises readily available scripts of two different TV shows containing all the episodes
of each series, Friends script and Game of Thrones script.
- We need not label the data exclusively, the model we use/train is going to be self-supervised and it will
use parts of the training data to train on and predict the next text.

# Models
Since the problem at hand requires the model to understand the initial input statement and then
generate the text for the next sentence, we plan to repurpose one of the pre-trained language models, such
as BART, so that their contextual word embeddings can facilitate a better understanding of the
training data as well as the input data after deployment.

# Examples:
F.R.I.E.N.D.S auto generated scipt:
![alt text]()
