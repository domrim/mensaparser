# mensaparser

This small utility parses the website https://essen.sw-ka.de and returns the food offers of the day (or any given day).

## Usage
Install dependecies with [poetry](https://python-poetry.org/) (`poetry install`) or with pip (`pip install -r requirements.txt`).
I recommend using an [virtualenv](https://virtualenv.pypa.io/en/latest/).

Run `mensaparser.get_food_plan()` to get food offers for "Mensa Adenauerring" for today (or next monday, if queried at weekend.)

