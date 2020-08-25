# cat-vs-dog-webapp
a deeplearning based binary classifier which classifies images of cats and dogs.the model is build using [pytorch framework](https://pytorch.org/) and trained on 
kaggles [cats-vs-dogs](<https://www.kaggle.com/c/dogs-vs-cats>) dataset, i also used kaggle free gpu for training purposes and using cpu for inference.
The frontend of the app is made using [bootstrap](https://getbootstrap.com/) and the model is served through flask as a backend [flask](https://flask.palletsprojects.com/en/1.1.x/).


![demo of project](demo/demo.gif)

# how to run the app
1. you need [python 3.7](https://www.python.org/) and above to run the app.
2. it's recommended to use [venv](https://youtu.be/APOPm01BVrk) or virtualenv to create virtual environment.
3. install all the dependency from requirement.txt file.
4. than from virtual environment run api.py file, that's it.
