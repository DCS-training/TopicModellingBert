# Topic Modelling with Bert

This is a repository for the "opic Modelling with Bert" course provided by Xan Cochran for the CDCS and based on material created by Pedro Jacobetty. Within this repository you are going to find all the material needed to attend this two-classes course once it will be ready. 
You are going to find a .pdf with the slides and a notebook file that we suggest you to run via Google Colab 


## Schedule

- Wednesday 3th April 2024 
  - 14:00 -- 16:00 
- Wednesday 10th April 2024 
  - 14:00 -- 16:00 


## SetUp 

For this course, the instructor is going to use Python via Google Colab. 
If you are going to use Google Colab you do not need to install anything but you will need to set up on it up (see below).
You can also set up locally on your computer via Anaconda or using Noteable 
Please notice that if you decide to use Noteable or run the notebook on your own machine you may encounter some problems in installing the libraries and you may not have enough ram to run it.  

### 1. Run the notebooks via GoogleColab

Open Google Colab: [https://colab.research.google.com](https://colab.research.google.com)
If you are not already logged you will be prompted to log-in via Gmail

#### Upload the Notebook to Google Colab
1. Go to the GitHub header and copy and paste the link to this repo and select the notebook you want to use and press enter

#### Using the Notebook
The Notebook contains paragraphs of explanatory text interspersed with grey cells containing code blocks. To run a code block and see the result:

1.  Place your cursor within the cell
2.  Click the 'Run' button on the top menu
4.  The results of running this code will appear below
5.  If the results don't appear immediately, check the icon in the browser tab. AN egg-timer icon indicates it is processing the code.
6.  It is best to follow the Notebook from top to bottom as some code blocks will depend on results from previous cells
7.  You can edit code blocks yourself and run them to see the results of your changes

All material collected here is free to use but is covered by a License: [![License: CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc/4.0/) license
   
#### Clearing the cells
To clear the results and run the code again you can use the 'Cell' menu on the top menu bar

1.  To clear the results of the current cell:  **Cell > Current Outputs > Clear**
2.  To clear the results of all cells:  **Cell > All Output > Clear**



### 2. Using Python On Noteable

1. Go to https://noteable.edina.ac.uk/login
2. Login with your EASE credentials
3. Select 'Standard Notebook (Python3)' as a personal notebook server and press start
4. Click the '+GitRepo'
5. Copy and Paste this repository URL https://github.com/DCS-training/IntroCausalInference as the Repository URL - you do not need to add in any other fields.
6. Decide where to locate the folder. By default, it will locate it in your home directory
7. Press 'Clone'
Congratulations you have now pulled the content of the repository on your Notable server space.


#### Installing the needed packages 
`!pip install bertopic 
!pip install keyphrase-vectorizers `


### 3.Installing Python via Anaconda

[Python][python] is great for general-purpose programming and is a popular language for scientific computing as well. Installing all of the packages required for this lessons individually can be a bit difficult, however, so we recommend the all-in-one installer [Anaconda][anaconda].

Regardless of how you choose to install it, please make sure you install Python version 3.x (preferably Python 3.11 or higher). 

#### Windows - [Video tutorial][video-windows]

1. Open [anaconda.com/download][anaconda-dl] with your web browser.

2. Download the Python 3 installer for Windows.

3. Double-click the executable and install Python 3 using _MOST_ of the default settings. The only exception is to check the **Make Anaconda the default Python** option.

#### macOS - [Video tutorial][video-mac]

1. Open [anaconda.com/download][anaconda-dl] with your web browser.

2. Download the Python 3 installer for macOS.

3. Install Python 3 using all of the defaults for installation.

#### Starting Python
To start Jupyter Notebook Open the Anaconda Navigator and Launch Jupyter Notebook.

If you wish, you can create a Python virtual environment and install all dependencies for the course by navigating to the course folder in the terminal and running `sh setup.sh`.

#### Upload the Notebook
1. Download the notebook on your machine
2. Go to Upload
3. Navigate to where you have downloaded your file
4. Select Upload again
5. Double-click on the uploaded file

#### Installing the needed packages 
`!pip install bertopic 
!pip install keyphrase-vectorizers `

[anaconda]: https://www.anaconda.com/distribution
[anaconda-dl]: https://www.anaconda.com/download/
[python]: https://python.org
[jupyter]: https://jupyter.org/index.html
[jupyter-install]: https://jupyter.org/install.html
[video-mac]: https://www.youtube.com/watch?v=TcSAln46u9U
[video-windows]: https://www.youtube.com/watch?v=xxQ0mzZ8UvA 



