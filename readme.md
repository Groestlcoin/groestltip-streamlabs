## Setup instructions

* Clone repository
* Activate your virtualenv
* `$ pip install -r requirements.txt`
* Create `config.ini` file with Streamlabs API key details
* `$ python db_create.py`
* `$ export FLASK_APP=run.py` or `$ set FLASK_APP=run.py`(Windows)
* `$ flask run`

### config.ini example

```
[GroestlTip]
secret_key = xxx
streamlabs_client_id = xxx
streamlabs_client_secret = xxx
redirect_uri = https://127.0.0.1:5000/launch
```

#### Related Links
* https://github.com/dursk/bitcoin-price-api
* https://github.com/Groestlcoin/electrum-grs/blob/master/electrum_grs/servers.json
