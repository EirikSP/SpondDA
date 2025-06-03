
## Running instructions

The code for this analysis is in a jupyter notebook. In order to run it yourself you should make a virtual environment and install the required python packages that are located in `requirements.txt`.\
These instructions assume you have a python installation with pip.

### Instructions

First you need to put the data files into the data folder of the project.

Then open a terminal in the folder for this project.\
<code>
pip install --user virtualenv \
python -m venv .venv \
</code>

Then activate the virtual environment \
Windows:\
<code>
.\\.venv\\Scripts\\activate \
</code>
Mac/Linux:\
<code>
source .venv/Scripts/activate \
</code>

Then you can install the packages by running: \
<code>
pip install -r requirements.txt \
</code>

You can then open the jupyter notebook by running:\
<code>
jupyter notebook analysis.ipynb \
</code>