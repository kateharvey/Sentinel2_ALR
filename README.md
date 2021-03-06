# ALR-Sentinel2

Details on Active Learning Regularization using SL2P algorithm: https://www.sciencedirect.com/science/article/pii/S0034425720306143
See LEAF-Toolbox: https://github.com/rfernand387/LEAF-Toolbox

Jupyter lab notebook with Python3 source code for LEAF-Toolbox using Google Earth Engine Python API.

Note: This is an exact copy of LEAF-ToolBox-SL2P for image by image products as implemented on February 10, 2021 16:00 EST https://code.earthengine.google.com/fd6bddb89803bd8ea45fdcad051f75cc


## Environment configuration:

**You will need an Anaconda environment configured as:**\
\>\>Anaconda \
\>\>conda create --name leaftoolbox \
\>\>conda activate leaftoolbox \
\>\>conda install -c conda-forge jupyterlab -y \
\>\>conda install -c conda-forge earthengine-api -y \
\>\>conda install -c conda-forge folium -y \
\>\>conda install -c conda-forge matplotlib -y \
\>\>conda install -c conda-forge pandas -y \
\>\>conda install -c conda-forge scikit-learn -y \
\>\>conda install -c conda-forge scipy -y \
\>\>conda install -c conda-forge tensorflow -y

**Then as follows to run the script in terminal window:**\
\>\>conda activate leaftoolbox \
\>\>jupyter lab
