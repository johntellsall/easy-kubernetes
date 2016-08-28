# aws-realtime-metrics
realtime metrics with Amazon SQS, Redis, and a bit of Python

Code adapted from https://github.com/miguelgrinberg/Flask-SocketIO -- thanks @miguelgrinberg!

## Install

virtualenv --python=$(which python2) venv
. venv/bin/activate
pip install -qr ./requirements.txt
sudo apt install chromium-chromedriver redis-server

### dev mode (local, no AWS)

gem install fake_sqs

## Run

python ./app.py


## Enjoy

open browser to http://127.0.0.1:5000/
