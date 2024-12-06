# sharescreen
A one file python script for screen sharing.

All you need is python3 installed with pip.
The script does require Flask and pyscreenshot but it will install those libraries automatically, so just run: 
python3 sharescreen.py

You can also specify a port like:
python3 sharescreen.py 89000
  
On windows, you might need to run the script two or three times untill all dependencies are installed.

## Running in a virtual environment

	`python3 -m venv venv`
	`source ./venv/bin/activate`
	`python sharescreen.py`

After creating a virtual environment, you can just run sharescreen.sh.
