# Dimensional-Reduction-on-Sea-Surface-Temperatur-Dataset-using-Principal-Component-Analysis
Apply PCA (Principal Component Analysis) to Pacific Sea Surface Temperature spatiotemporal data. The purpose of the analysis is to get the most PC that corresponds to the most dominant pattern of phenomenon (PC which represents the most variance).

### Required Libraries
Please make sure that the followings libraries is already installed in your python environment:
1. Numpy
2. Matplotlib
3. Scipy
4. Pylab
5. Basemap
6. cm

### Basemap Installation
Basemap is a great tool for creating maps using python in a simple way. It's a matplotlib extension, so it has got all its features to create data visualizations, and adds the geographical projections and some datasets to be able to plot coast lines, countries, and so on directly from the library.

In some my colleagues' python environment, installing basemap is a bit tricky. Basemap could possibly impact your existing libraries in your environment and turn your libraries under error (Some errors might be hard to identify). Consequently, I fully recommend you creating a new environment, install/upgrade basic libraries, and install Basemap (Don't install basemap on your base environement).

To install Basemap package with conda run:
<br>`conda install -c anaconda basemap`

or, download the package first: [here](https://www.lfd.uci.edu/~gohlke/pythonlibs/#basemap), and:
<br>`pip install basemap-1.0.8-cp34-none-win_amd64.whl`

### Licence
This project is under [MIT licence](https://opensource.org/licenses/MIT). Please feel free to use, copy, modify, merge, publish, and distribute. It's my pleasure~.
