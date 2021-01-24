## Guideline for using the Notebooks


1) All code is written in Python 3.8.


2) Within each notebook make sure to run all cells top to bottom.


3) Be patient. Some graphics might need a few seconds to render.


4) Cells should not be executed twice in a row. Clear output and re-execute all previous cells instead.


5) Each notebook can be executed independentently.


6) There is no reason to run all notebooks in order, since all output already exists as files within the 'data' folder.


7) The API-querry output from Google is already stored in the 'place_details' folder and does not need to be executed.


8) Make sure the required packages are installed on your system. Required packages for each notebook are stated in alphabetic order within the first code cell.


--> If your system has problems installing python-levenshtein you most likely miss the required C environment. When using anaconda try entering in your prompt:

"""
conda install -c conda-forge python-levenshtein
"""

--> The Kepler-Python-Jupyter Module requires several packages to be pre-installed.
--> Entering the following code into the anaconda prompt worked out for me:

"""
pip install wheel
pip install pipwin
pipwin install numpy
pipwin install pandas
pipwin install shapely
pipwin install gdal
pipwin install fiona
pipwin install pyproj
pipwin install six
pipwin install rtree
pipwin install geopandas
"""


9) '' is used for indexing, variables and parameters.

10) "" is used for actual strings.

11) Comments start with a #.

