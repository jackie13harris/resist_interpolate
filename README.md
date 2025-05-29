This folder includes resistivity data and interpolated resistivity data in .csv files, as well as a Jupyter notebook that can 
interpolate resistivity sounding data from a Wenner array to match required spacing from the Resist software (Craig Jones field geophysics).

The intended purpose of this repository is primarily for future Carleton College geophysics students using our Bison resistivity instruments to make field data modelable with Resist.

.csv files are to present example data. Any inputted data should follow the same two-column format, with electrode spacing in the first column and apparent resistivity (NOT raw field measurements) in the second column.

The notebook includes code to define parameters, functions that import data from the folder and perform the interpolation (default cubic spline), a section to create new .csv files with the data, and a section to
test the interpolation results by graphing input data with output data.
