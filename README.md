# AI Sokoban Solver
This project was developed in the context of the [Artificial Intelligence](https://www.ua.pt/en/uc/12287) curricular unit, part of the Informatics Engineering Degree of [University of Aveiro](https://www.ua.pt/).

The goal of the project was to develop an AI solver for the Sokoban Game, implemented in Python.

![Demo](https://github.com/dgomes/iia-ia-sokoban/raw/master/data/sokoban_screenshot.png)

## How to install

Make sure you are running Python 3.5 or higher

1. Create a virtual environment (venv)
```bash
python3 -m venv venv
```

2. Activate the virtual environment (you need to repeat this step, and this step only, every time you start a new terminal/session):
```bash
source venv/bin/activate
```

3. Install the game requirements:
```bash
pip install -r requirements.txt
```

## How to play

open 3 terminals:

`$ python3 server.py`

`$ python3 viewer.py`

`$ python3 client.py`

to play using the sample client make sure the client pygame hidden window has focus

### Details

Further information can be found on the final report, that is available (in pdf format) [here](https://github.com/itskikat/ai-sokoban-solver/blob/main/Presentation.pdf).

# Credits

Thank you [Kenney](https://www.kenney.nl/assets/sokoban) for the sprites! 

