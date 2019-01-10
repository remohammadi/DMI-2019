# DMI-2019

## Setup Workspace
```
git clone https://github.com/remohammadi/DMI-2019.git
python3 -m venv .pyenv
source .pyenv/bin/activate

cd DMI-2019/
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
jupyter notebook
```

Visit http://localhost:8888/notebooks/Operalization.ipynb

## Download the Required Data Files
```
cd data
curl -O https://jeffreyatw.com/static/mbfc/sources.json
curl -O https://storage.googleapis.com/twitter-election-integrity/hashed/iranian/iranian_users_csv_hashed.zip && unzip iranian_users_csv_hashed.zip && rm iranian_users_csv_hashed.zip && mv iranian_users_csv_hashed iranian_users.csv
curl -O https://storage.googleapis.com/twitter-election-integrity/hashed/iranian/iranian_tweets_csv_hashed.zip && unzip iranian_tweets_csv_hashed.zip && rm iranian_tweets_csv_hashed.zip && mv iranian_tweets_csv_hashed.csv iranian_tweets.csv
```
