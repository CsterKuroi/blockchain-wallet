# unichain-client

### Quick Start

```
sudo pip3 install -r requirements.txt
[optional]python3 config.py
[optional]vim .unichain-account <modify the default config and save>
python3 manage.py
```

Then, open `localhost:5000` in your browser

### Default Config (.unichain-account)

```
{
    "server": {
        "port": "9984",
        "host": "localhost"
    },
    "username": "user",
    "keypair": {
        "public":  "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx",
        "private": "yyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyy"
    }
}
```