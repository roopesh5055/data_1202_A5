# Python Experiment files
The jupyter notebook python files in this directory are meant to explore MySQL db connection and querying using python and exploration of pandas package.

## How to run
* step 1: Clone this directory to your local machine.
* step 2: Open jupyter notebook.
* step 3: Open the notebook files and explore the codes.

## Prerequisites
python 3.x and jupyter notebook

### MySQL_connection_and_queris.ipynb
This file contains the python codes to build connection to sql database, run queries and load the results into dataframes, and use of 'where' clause in python.
Before running all the cells just update the mysql credentials to your db credentials
```## sql connection
engine = create_engine('mysql+pymysql://<user>:<password>@<host>/<db_name>')```

### Explore_pandas.ipynb
This notebook file is to explore the different functionality of pandas framework in python. That includes adding new columns, concatinating, and appending of dataframes. It also includes the group by functionality of python pandas.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
