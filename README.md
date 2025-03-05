Pre-requisites: Python 3

To run, follow the instructions below:

1. Download the code from Github (clone or download)
2. Unzip the downloaded file
3. Enter the directory of unzipped files
4. Run the command `python3 -m venv venv` to create a new virtual environment in the directory
5. Run the command `source venv/bin/activate` to enter the virtual environment (on Windows run `venv\Scripts\activate` instead)
6. Run the command `python3 -m pip install -r requirements.txt` to install prerequisite packages
7. Run the command `python3 main.py` to begin the game


Controls: 
* W - Move Forward 
* A - Rotate Left
* S - Move Backward
* D - Rotate Right
* SPACE - Shoot

When you collide with an asteroid the console will print "Game Over" and exit the game. 
