# A Quickstart Guide to PyMC3
A PyData Chicago tutorial
8/26/16
([Video](https://www.youtube.com/watch?v=rZvro4-nFIk))

Follow the steps below to get set up.

Step 1: Clone this repo

Step 2: Go into the directory of this repo in your terminal

``` $ cd pymc3_quickstart_guide```

### Conda Instructions:

Note: if you want to use python 2.7, add this line `- python=2.7` to the dependencies in the yml file.

Step 3: Create a new conda environment

``` $ conda env create```

Step 4: Activate your virtual environment

``` $ source activate pymc3_quickstart_guide```

(To deactivate, type `deactivate source`)

Step 5: Start your local Jupyter server

``` $ jupyter notebook```

### virtualenv and pip instructions

Step 3: Create a virtual environment

``` $ virtualenv venv```

Step 4: Activate your virtual environment

``` $ source venv/bin/activate```

(To deactivate, type `deactivate`)

Step 5: Install requirements

``` $ pip install -r requirements.txt```

Note: you should use a version of pip > 8.1, If your pip is older, update pip via `pip install --upgrade pip`

Step 6: Start your local Jupyter server

``` $ jupyter notebook```
