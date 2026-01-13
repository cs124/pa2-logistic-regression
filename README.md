# PA2 - Logistic Regression

## Recommended before Starting

We recommend checking out the following before getting started on PA2 Logistic Regression:

* The Week 3 videos and slides on Logistic Regression.
* Chapter 5 of Jurafsky and Martin (3rd ed.), particularly sections 5.1-5.4

## Cloning the Assignment

### Jupyter Notebook

You can get started using the same steps you followed for PA1. To recap,
you'll want to:

1. Open a terminal (terminal for macOS and Linux, 
   Ubuntu for Windows for Windows, or SSH into Rice/Myth) the same way you 
   did for PA1. 

1. Clone the git repository for PA2 (this repository) into a folder of your 
   choice by typing this in your terminal:
      
        git clone https://github.com/cs124/pa2-logistic-regression.git

2. Enter the project root directory and activate your cs124 conda environment by
   doing:
   
        cd pa2-logistic-regression
        conda activate cs124
   
    You should now see `(cs124)` in front of your shell prompt. 

   You'll need to do this every time you open a new terminal and re-start your
   notebook server. You should have already created this conda environment 
   as part of PA0. If not, and you encounter an error, please go back and 
   follow the instructions there.

3. Start up your jupyter notebook server

        jupyter notebook

4. A window should open automatically in your default browser. If it didn't,
    the terminal output should contain a URL you can use to open the
    notebook in a browser of your choice.
   
5. From the Jupyter notebook file explorer window that opens, click on the
pa2.ipynb file to open and edit it.

### Google Colaboratory

1. Go to [colab.research.google.com](http://colab.research.google.com). 
   If prompted to open a notebook, hit cancel for now. You should double-check 
   that you are logged in to your Stanford Google account. If not, you can 
   switch accounts in the top right.
   
2. Now go to File->Open Notebook. Go to the GitHub tab. It will ask you to log 
   in to your GitHub account (if you don't have one it is easy to make one).
   Once you've done that, copy and paste the URL: 
   https://github.com/cs124/pa2-logistic-regression into the search box and hit enter. 
   It should show:
   
            Repository: cs124/pa2-logistic-regression
            Branch:  Main

   Click on pa2.ipynb below to load the notebook.
      

## Submitting your Solution

### macOS/Linux

1. You can run the submission cell in the Jupyter notebook to zip up your
solution for you. It should generate a zip file `submission.zip`.
   
2. Upload the zip file as your solution to the PA2 Logistic Regression assignment in 
   Gradescope (http://www.gradescope.com).

### Ubuntu for Windows

1. You can run the cell at the bottom of the Jupyter notebook to zip up your
solution for you. It should generate a zip file `submission.zip`.
   
2. Run the following command to transfer that zip file over from WSL to your local computer:

      cp ~/cs124/pa2-logistic-regression/submission.zip /mnt/c/Users/YOUR_USER_NAME/OneDrive/Desktop/

   Note that you may want to replace OneDrive/Desktop/ with another destination folder based on your preferences.

3. Upload the zip file as your solution to the PA2 Logistic Regression assignment in 
   Gradescope (http://www.gradescope.com).

### Rice/Myth

1. You can run the cell at the bottom of the Jupyter notebook to zip up your
solution for you. It should generate a zip file `submission.zip`.
   
2. You will then need to download/copy the zip file from Rice/Myth to your
local machine.
   
   - __[macOS/Linux/Ubuntu for Windows]__
    
      After you have created the submission zip, first, run this command to find where the submission zip is:

            pwd

      This should return something like

            /afs/.ir/users/YOUR/SUNET/ID/cs124/pa2-logistic-regression

      Copy that command and append submission.zip to it:

            /afs/.ir/users/YOUR/SUNET/ID/cs124/pa2-logistic-regression/submission.zip

      Then, cd into a local folder where you'd like to save the submission zip, and use the following command to copy the zip from Myth to your local machine:

         scp -r [SUNet]@[rice/myth][rice/myth machine number].stanford.edu:/afs/.ir/users/YOUR/SUNET/ID/cs124/pa2-logistic-regression/submission.zip .
      
      You can replace . with a relative path to a local directory you'd like to copy the zip file to.

   - __[Windows]__ PSCP is another utility that should have been installed
    automatically when you installed PuTTY earlier. Find and run it. In the
     terminal window, you can run the command:
     
            pscp [Your SUNet]@rice.stanford.edu:/path/to/submission.zip c:\temp\submission.zip
    
    to download the file from Rice/Myth to your local machine. You should now
   be able to access the file locally at c:\temp\submission.zip
   
3. Upload the zip file as your solution to the PA2 Logistic Regression assignment in 
   Gradescope (http://www.gradescope.com).

### Google Colaboratory

1. Once you've saved all your changes, go to File->Download .ipynb to download
your notebook file to your local machine.
2. If your solution required any extra files, make sure they were located in
pa2-logistic-regression/deps. Go to the file explorer on the left-hand side and download
those as well.
3. Once you have pa2.ipynb and any deps files you need saved locally,
create a zip file (either from your OS's file explorer or the terminal), making
sure that it has the following structure:
   
        deps/
        pa2.ipynb

3. Upload the zip file as your solution to the PA2 Logistic Regression assignment in 
   Gradescope (http://www.gradescope.com).