Files for a Flask app to use as an API for returning Simpsons quotes similar to
input text.

create_models.py must be ran to generate models before initiating the app

Parameters in create_models.py can be changed to allow for a more complex model
and better quote prediction.

Dataset Taken from [Kaggle](https://www.kaggle.com/pierremegret/dialogue-lines-of-the-simpsons) and filtered to only include quotes with at least 3 lemmas

Currently Deployed with heroku at https://simpsons-quote-predictor.herokuapp.com/input?input_text=
To find a quote similar to input text, just add your input to the end of the url
If nothing is added a quote will be returned at random

These files were created in colaboration with Michael Curry, Luke Townsend, and Michael Gospodinoff
