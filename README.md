# Postmates API (Solutions Engineering take-home test)

# Intro
Solution to scenario:
https://gist.github.com/davemurphysf/f000915964aab8eba8e4c847cb7559c8

This project runs on Flask (https://flask.palletsprojects.com/) and Python 2.7.16.

## Install virtualenv and activate environment
 $: pip install virtualenv
 $: python -m virtualenv venv
 $: . venv/bin/activate

## Install dependencies
 $: pip install -r requirements.txt

## Set environment vars
 $: export FLASK_APP=postmates.py  
 $: export FLASK_ENV=development

## Run server
 $: flask run  

 Application is available at http://localhost:5000 and will bootstrap with sample order.json.

 Thank you!  

 Cliff Fong
 cliffordfong@gmail.com
