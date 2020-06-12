### Date created
June 11, 2020



### Project Title
US Bikeshare Data Analaysis CLI Program Project



### Description

`bikeshare` is a cli program that explores the bikeshare data of Chicago, New York and Washginton cities, which is provided in the embedded data files.

This program is implemented using Ptyon Click 7.0 and above. 


### Files used

```shell
├── MANIFEST.in
├── bikeshare
│   ├── __init__.py
│   ├── cli.py
│   └── helpfunc.py
├── requirements.txt
├── setup.py
```

### Installation

Run this in Linux or MacOS terminal to clone the repo and install the package as CLI command.

`git clone https://github.com/catelinn/pdsnd_github.git bikeshare_cli && cd bikeshare_cli && pip install .`


### Usage

- `bikeshare -h`
- `bikeshare filter -h`


#### Example:

- View data of Chicago in January, February and March on Wednesday and Friday: 

    `bikeshare filter -c chicago -m 123 -d 35` 

- View data of New York of all months and all days:
   
   `bikeshare filter -c new\ york -m 0 -d 0`

- Enter OPTIONS to filter data in interactive mode: 

    `bikeshare filter`


### Credits
[Comparing Python Command-Line Parsing Libraries – Argparse, Docopt, and Click
by Kyle Purdon](https://realpython.com/comparing-python-command-line-parsing-libraries-argparse-docopt-click/)



[Sebastian Vetter - Click: A Pleasure To Write, A Pleasure To Use at PyCon US 2016 Talk](https://www.youtube.com/watch?v=SDyHLG2ltSY)

[Click example for PyCon US 2016 talk.](https://github.com/elbaschid/pycon-talk-click-example/blob/master/ad_notifier/cli.py)

