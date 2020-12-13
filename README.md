# CourseProject

Explain your model
For the competition I used the BERT(Bidirectional Encoder Representations from Transformers) model. This model is a cutting edge model for classification. BERT's main innovation is applying the bidirectional training of Transformer, a popular attention model, to language modeling. 

How I performed the training:

Since BERT training on CPU was incredably slow, I utilized a google cloud VM to train the model on the gpu, this enabled much faster training speeds and more experimentation with parameters and tuning. 

Experiments with other methods:

Prior to using BERT, I tried to create my own model and tunings, however they failed to come close to the baseline, so I expanded my options and opted to utilize BERT. 


demo video: 
https://drive.google.com/file/d/1LIkJRzyLRYKK2roMzF5CP208Hlj24ehw/view?usp=sharing
