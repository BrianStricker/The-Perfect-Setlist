**About**

This project is based on the question: Can I find ‘the perfect setlist’?

As a singer/acoustic-electric guitar player I have often wondered if there was a better way to create a great or perfect setlist, other than playing my personal favorites or copying from other entertainers in the local biz. The following is my quest to do so using Spotify and Billboard statistics from the 60s, 70s and 80s. I chose these decades because they are the music I grew up on, and tend to be much more ‘acoustically’ friendly than the electronically-infused songs of today.

Here are a few of the attributes considered when seeking the best correlating relationships for this endeavor:
•	Acousticness
•	Danceability
•	Energy
•	Top 20 (of their decade)
•	Artist
•	Track
•	Valence

These, and all other terms and definitions can be found in the **Data Dictionary** that I’ve compiled for the reader. It will explain further what each data variable means and how it is measured or applied for results. It will also define music terminology used throughout the project.

CSVs being used were originally downloaded from the following sites:

https://www.kaggle.com/datasets/theoverman/the-spotify-hit-predictor-dataset

https://www.kaggle.com/datasets/emilynallen/top-20-songs-1970s2000s-w-audio-features

Billboard 1960s: https://bit.ly/2KxBq67
Billboard 1970s: https://bit.ly/2GQoIA8
Billboard 1980s: https://bit.ly/2mCCNFt

**Running the Project**
The entire project was created in Jupyter Notebook.
There are three separate notebooks that comprise the entirety of the project. They are:
The Perfect Setlist I.ipynb, 
The Perfect Setlist II.ipynb
The Perfect Setlist III.ipynb.

If you already have a preferred IDE, simply clone this repo and open the above notebooks. If you have Anaconda installed, simply use your base Conda environment.

**HOW TO RUN IN JUPYTER NOTEBOOK**
1.	Clone the Repository
2.	Save the Folder
3.	Open Jupyter Notebook from the command line or start menu.
4.	Open 
•	The Perfect Setlist I.ipynb
•	The Perfect Setlist II.ipynb 
•	The Perfect Setlist III.ipynb

**HOW TO RUN THE PROGRAM IN PYTHON**
1. Clone the Repository
2. Save the Folder
3. Open saved Repository in your terminal or IDE
4. Run ‘The Perfect Setlist I.ipynb (then the next two)
*(if you don’t have Python installed a link is below)*

All original datasets analyzed in the project are included and can also be obtained from the links above. They are named:
•	dataset-of-60s.csv
•	dataset-of-70s.csv
•	dataset-of-80s.csv
•	Top 20 All Decades.csv 

All newly written datasets are included with the project, as well. They are:
•	Three Decades.csv
•	Top Twenty.csv
•	Final.csv

Libraries are listed in the ‘Requirements.txt’ folder.
This project uses: 
•	pandas as pd 
•	numpy as np
•	seaborn as sns
•	matplotlib.pyplot as plt 
•	plotly as pypl 
•	plotly.express as px

**Installation**
Before you begin, ensure you have met the following requirements:
•	You have installed Python. This project was developed in Jupyter Notebook using Python 3.10.9 (packaged by Anaconda Inc.). If you don't have Python installed or if you need to upgrade your current version, you can download it from the official [Python website](https://www.python.org/downloads/)
•	You have installed Git, which is necessary to clone the repository. If you don't have Git installed, you can download it from the [official Git website.](https://git-scm.com/downloads)
Follow these steps to run the project on your local machine:
1.	Clone the repository
2. Navigate to the directory where you want the cloned repository to be placed by using the cd command in your terminal followed by the path of the directory.
Then you can clone this repository by running the following command in your terminal:
#git clone  https://github.com/BrianStricker/The-Perfect-Setlist**
3.	**Navigate to the cloned directory**
Change your current directory to the cloned repository's directory: The-Perfect-Setlist
4.	**Set up a virtual environment**
It's recommended to create a virtual environment to keep the project's dependencies isolated from your system's Python environment. You can create a virtual environment using the following command:

On Windows:
python -m venv venv

On macOS and Linux:
python3 -m venv venv

This will create a new virtual environment named venv in your current directory.

4.	**Activate the virtual environment**
Activate the virtual environment using the following command:

On Windows:
.\venv\Scripts\activate

On macOS and Linux:
source venv/bin/activate

Your prompt should change to indicate that you are now operating within a Python virtual environment.

5.	**Install the required packages**
Install the required packages by running the following command:
pip install -r requirements.txt
You're now ready to run the project!

6.	**Run the The_Perfect_Setlist.ipynb file:**

Again, if you have Jupyter Notebook installed, enter jupyter notebook and open the .ipynb file. If you would like to install it the link with instructions is: 

[Project Jupyter | Installing Jupyter](https://jupyter.org/install)
If you are using Visual Studio Code, open the .ipynb file and run the cells using the run button that appears at the top left of each cell. If you need to install it the link with instructions is: 
[Download Visual Studio Tools - Install Free for Windows, Mac, Linux (microsoft.com)](https://visualstudio.microsoft.com/downloads/)
If you are using VS Code and don’t have Anaconda downloaded
The Python extension for VS Code comes with Jupyter and Pylance extensions, which enable you to work with Jupyter notebooks in VS Code. If you don’t have these, install them. Here is a link with instructions: [https://code.visualstudio.com/docs/languages/python](https://code.visualstudio.com/docs/languages/python) . 
Then you can select any Python environment that has Jupyter installed. Again, stick with base Conda when you can.

To deactivate the virtual environment when you're finished, simply type ‘deactivate’ in your terminal.

