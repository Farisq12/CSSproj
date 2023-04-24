# README #
### What is this repository for? ###
	 With a rise in fake news being created and the development of artificial intelligence, the gradually
	 increasing use of AI to make fake news is becoming a problem. Grover is a dual function AI with the 
	 first purpose of generating full length fake articles the purpose of not only testing AIs against the 
	 detection of fake news, but also analyzing the impact/trustworthiness people would put into the AI 
	 generated Articles often finding that the articles written by Grover were more trust than ones 
	 written by human sources. The other part of Grover is focused on detecting the source of fake news. 
	 With a focus on text style articles Grover is not so much a fact checker as it is more an AI/human 
	 discriminator. This part of Grover aims to not necessarily derail fake news, but rather lower the 
	 effects of things like the backfire effect and confirmation which lead people to believing new if it 
	 confirms the things, they already perceive to be true. While testing out the Grover AI, we found that 
	 while it is good at creating articles given certain information, the discrimination part of the service 
	 was not working well with articles made by ChatGPT or other ais and edited by a human. 
	 This repository is for working on a way to imporve on the current Grover System through authentifaication 
	 using a hasheys. 
	 
This repository focuses on adding integrity to the original files that are altered by neural fake news generators such as grover.
By implementing a hash key function that detects if a file has been altered or not it can add further security to grover in detecting
neural fake news.

### How do I get set up? ###

**First clone the repoistory onto your local machine**

**How to run**	

Prerequisites:

You must be able to run a .ipnyb file and vscode or other another ide of your choice that supports juypeter notebooks. If you already have this set up, ignore the guide. If you do not, here is a guide:

**jupyter notebook installation guide**
Ensure that you have the following installed on your local machine:

Python 3 (version 3.6 or later): You can download and install Python from the official website.
pip: This is the package installer for Python. It usually comes pre-installed with Python. You can verify if pip is installed by running pip --version in your terminal/command prompt.
Step-by-Step Instructions

Step 1: Install Jupyter Notebook
Open your terminal (Mac/Linux) or command prompt (Windows).
Run the following command to install Jupyter Notebook:
Copy code:
``pip install notebook``

Step 2: Launch Jupyter Notebook
Navigate to the folder where your .ipynb file is located using the terminal or command prompt.
Run the following command to start Jupyter Notebook:
Copy code
``jupyter notebook``

This will launch a new browser window or open a new tab in your default web browser, displaying the Jupyter Notebook interface.

Step 3: Open and Run Your .ipynb File
In the Jupyter Notebook interface, locate and click on the .ipynb file you want to run. This will open the file in a new browser tab.
To run a code cell in the Jupyter Notebook, click on the cell and press Shift + Enter or click the "Run" button in the toolbar.
Continue executing the cells in the notebook by selecting and running them one by one or by clicking "Kernel" > "Restart & Run All" in the menu bar to run all cells in the notebook.

**for pdf parsing functionality**
You must also have PyPDF2 installed for pdf parsing functionality, it's not truly needed for grover since grover itself only uses
.txt files, but to use it use the command: ``pip install PyPDF2``


#### Deployment instructions ####

**To run detector.ipnyb**

After having the enviorment set up simply open the detector.ipnyb file and run the cells.

If you want to try adding your own articles simply add them to the repo or to the docs and change the filepath of it on the input and output:

``input_path = "(yourfilepath)"``

``output_path = "(yourfilepath)"``


### Contribution guidelines ###

	* Reasearch
		* Emmanuel S.
		
	* Coders
		* Faris Q.
		* Ricardo N.
	* Article Developers
		* Lois H.