# Discrete Choice Analysis: micro-econometrics and machine learning approaches
## *Machine learning approaches for discrete choice analysis*

- **Teacher:** Dr. Sander van Cranenburgh
- **Teacher assistants:** Francisco Garrido-Valenzuela and Lucas Spierenburg

## General aim
Discrete choice analysis (DCA) has become one of the most important frameworks for transportation modelling. Using DCA, the researcher or analyst is able to estimate the influence of all sorts of factors on travel choice behavior, and to predict mobility patterns and market shares for transport-related services; all this, in a quantitative, statistically rigorous way with deep roots in economics and the behavioral sciences. As such, DCA is indispensable for the underpinning of many transport policies and plans.

In this course, we will cover two different perspectives on DCA: the conventional, econometrics-based perspective (also called Discrete choice theory); and a more novel perspective which is gaining ground rapidly, based on recent advances in Machine learning. This combination makes this course unique, compared to other choice modelling courses taught in the Transport community.

This course will contain a mix of theory, implementation guidelines, and hands-on exercises to be completed during the course and under supervision of the lecturer.

**This repo cover the materials for the days 3 and 4**

## Schedule

### Day 3 (July 7th) – Machine learning approaches for discrete choice analysis (Part 1) (Van Cranenburgh)
**Time**: 10.00 – 16.00 h<br>
**Room**: D2 (ground floor), TPM, Jaffalaan 5
- Introduction to machine learning for choice modellers
- Artificial neural networks & Training
- Lab session 1 (jupyter notebook)


### Day 4 (July 8th) – Machine learning approaches for discrete choice analysis (Part 1) (Van Cranenburgh)
**Time**: 10.00 – 16.00 h<br>
**Room**: D2 (ground floor), TPM, Jaffalaan 5
- Explainable AI techniques
- Hybrid models and SHAP values
- Data requirements for training ANNs
- Exercise 2 (Jupyter notebook)

# Instructions to set-up your workspace

To properly run the Python notebooks contained in this repo, it is recommended to use Google Colab. But, if you wish to use your local environment (your computer), you can also do so by following certain recommendations.

## Option 1: Google Colab

**Minimal requirements:**
- A Google account
- Web browser
- Internet connection

### Steps
- **Step 1:** Download this repo to your computer. On the top of this site, click on the green button "Code" and then "Download ZIP" (See numbers 1 and 2 on the following image).
<p align="center">
  <img width="500" src="https://github.com/FGarridoV/resources/blob/main/Downloading%20repo.png">
</p>

- **Step 2:** Go to [http://colab.research.google.com](http://colab.research.google.com)
- **Step 3:** Sign in with your google account (if you are already signed in, skip this step)
- **Step 4:** Upload the Python notebook you would like to work on. Click on "Upload" tab and then on "Choose file" (See numbers 1 and 2 on the following figure). Then navigate on your folders (from download of **Step 1**) to the Python Notebook (.ipynb) you would like to open (e.g. Lecture_1.ipynb).
<p align="center">
  <img width="400" src="https://github.com/FGarridoV/resources/blob/main/Opening%20ipynb.png?raw=true">
</p>

- **Step 5:** Uncomment the two lines related to Colab set-up in your notebook. Then, run this cell and wait until finish.
[ADD IMAGE EXAMPLE HERE]

- **Step 6:** We are ready! Now, you can run the rest of the file.

**Notes:**
- You can run cell by cell by clicking the play button next to it. Alternative, press ctrl+F9 to run all cells at once.
- The uploaded notebook file will be stored in Google Drive's account (results of **Step 4**)
- If you close the session, look the uploaded file, and you must do Step 5 again.


## Option 2: Local environment

**Minimal requirements:**
- A Python version installed (3.8 or newer)
- An IPython (notebook) enviroment installed in your computer (Jupyter, VSCode or alternatives)
- Basic skills in virtual enviroments (Only if you don't what to mix your current dependencies)

### Steps
- **Step 1:** Clone or download this repo to your computer (see **Step 1** on Colab section).
- **Step 2:** Depends on if you would like to install the dependecies separate:
  - **Step 2.a:** If you want to create a virtual environment (venv):
    - Creates new a virtual environment (venv) and install the `requirements.txt` file in it.
    - Open the notebook with your software of preference and run the notebook in the venv created.
  - **Step 2.b:** If not, open the Python notebook you would like to open, uncomment the two lines related to local set-up in your notebook and run 


