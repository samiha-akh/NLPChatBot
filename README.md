# NLPChatBot


I trained the Deep NLP dataset with the Sequential model at first. The dataset
contains two CSV files; one contains 80 user responses, and the other contains 125
resumes. Using this data, this bot determines if the user needs immediate help or
can just keep chatting with the bot. From the Sequential model, I got an
accuracy score of 0.7256. Later, I added an LSTM layer and got an overfitting score.
By adding Dropout, I finally got a score of 0.7134.


![Accuracy](https://github.com/samiha-akh/NLPChatBot/assets/156142386/53b9b8be-4ee5-4f6e-9313-65f31e07600e)
