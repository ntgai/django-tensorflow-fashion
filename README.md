# django-tensorflow-fashion

Simple Django app for predicting image with trained Fashion MNIST data model

<div>
<img height="350" width="350" src="https://s3.amazonaws.com/clarityfm-production/attachments/6605/default/django.png?1442839704"/>
<img height="250" width="350" src="https://blog.keras.io/img/keras-tensorflow-logo.jpg"/></div>

## Installation
Assuming python3, github already installed on your computer, and pip3 is active

```
# installing virtualenv for isolated environment
pip3 install virtualenv

# cloning from github to your development folder
git clone https://github.com/ntgai/django-tensorflow-fashion.git

# virtualenv activation
cd django-tensorflow-fashion
source bin/activate

# installing requirements
cd tensor
pip3 install -r requirements.txt

# migrate to dbsqlite
python3 manage.py migrate

# running on localserver
python3 manage.py runserver
```

## Running
127.0.0.1 - confirms tensorflow installed and shows version

127.0.0.1:8000/predict - simple form, where you enter real picture object and url from web, and it predicts with pretrained model. 

## Testing

Ankle Boot

Pullover

T-shirt

As noted in academic papers, this model is not great for the public picture which is outside in fashion mnist dataset. This is a future task to be able to convert any picture to fashion mnist shape and form.
