# wolfd
Forward jabber to slack.

## Installation
```
git clone git@github.com:taroncodesthings/wolfd.git
cd wolfd
```
Create a virtualenv
```
virtualenv venv
. venv/bin/activate
pip install -r requirements.txt
python setup.py
```

## Configuration
There is a wolfd_sample.yaml in the top level directory of the repository. Copy this to the homedir of the user you are running wolfd as, rename to .wolfd.yaml and edit as needed.

## Run the daemon
```
wolfd
```
