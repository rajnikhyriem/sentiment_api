# sentiment_api
Sentiment analysis REST API using Django and Keras

Implements a Bidirectional LSTM that utilises word and character embeddings to classify sentiment as positive or negative.

Getting Setup
-------------
Clone the repo:
```
git clone git@github.com:NickLeoMartin/sentiment_api.git
```

Head into the repo and create and activate a virtual environment:
```
virtualenv --no-site-packages -p python3 venv
source venv/bin/activate
```

Install the packages used:
```
pip install -r requirements.txt
```

Running The Repo Locally:
-------------------------
Access the frontend locally:
```
./manage.py runserver 
```

To-Do
-----
- [x] Simple Boostrap interface
- [x] Basic Class-based API endpoint
- [x] Ajax call to API endpoint
- [x] BaseModel class
- [x] Bidirectional LSTM with word and character embeddings
- [ ] Downloading script for short-text sentiment data
- [ ] Dataset wrapper
- [ ] Preprocessing dataset
- [ ] Model training and storage
- [ ] Local loading and prediction through API endpoint
- [ ] Dockerize project
- [ ] Deploy on server

