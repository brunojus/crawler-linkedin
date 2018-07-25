# LinkedIn Crawler Connections

Linkedin crawler to search and collect my connections

## Install

```bash
$ sudo apt-get update && sudo apt-get upgrade
$ sudo apt-get install virtualenv python3 python3-dev python-dev gcc libpq-dev libssl-dev libffi-dev build-essentials
$ virtualenv -p /usr/bin/python3 .env
$ source .env/bin/activate
$ pip install -r requirements.txt
```

## How to use

```bash
$ python linkedin.py <linkedin-username> <linkedin-password>
```


