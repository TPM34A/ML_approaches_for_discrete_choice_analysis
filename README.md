# Discrete Choice Analysis: micro-econometrics and machine learning approaches
## *Machine learning approaches for discrete choice analysis*

- **Lecturer:** Dr. Sander van Cranenburgh
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
- Lab session 1 (Python notebook)


### Day 4 (July 8th) – Machine learning approaches for discrete choice analysis (Part 1) (Van Cranenburgh)
**Time**: 10.00 – 16.00 h<br>
**Room**: D2 (ground floor), TPM, Jaffalaan 5
- Explainable AI techniques
- Hybrid models and SHAP values
- Data requirements for training ANNs
- Lab session 2 (Python notebook)

# Instructions to set-up your workspace

To properly run the Python notebooks in this repo, we recommend to use **Google Colab**. However, if you wish to run the notebooks on your local environment (i.e. your own laptop), then following the instructions provided under **option 2**.

## Option 1: Google Colab (recommended)

**Minimal requirements:**
- A Google account
- Google Chrome web browser
- Internet connection

### Steps
- **Step 1:** Download this repo to your computer. On the top of this site, click on the green button "Code" and then "Download ZIP" (See numbers 1 and 2 on the following image). Unzip this file in a working folder of your own choice.
<p align="center">
  <img width="500" src="https://github.com/FGarridoV/resources/blob/main/Downloading%20repo.png">
</p>

- **Step 2:** Go to [http://colab.research.google.com](http://colab.research.google.com)
- **Step 3:** Sign in with your Google account (if you are already signed in, skip this step). If you do not have a Google account, you must (temporarily) create one.
- **Step 4:** Upload the Python notebook you want to work on to Colab. Click on the "Upload" tab and then on the "Choose file" tab, see numbers 1 and 2 on the figure below. Then, navigate to your working folder (**Step 1**) and select the Python notebook (.ipynb) you want to work on(e.g. Lab session 1.ipynb).
<p align="center">
  <img width="400" src="https://github.com/FGarridoV/resources/blob/main/Opening%20ipynb.png?raw=true">
</p>

- **Step 5:** Once open, click on "View" >> "Expand sections" on menu bar.

- **Step 6:** **Importantly**, uncomment (i.e. remove the '#') the lines related to Colab set-up in your notebook, see the figure below. Run this cell and wait until finish.
<p align="center">
  <img width="400" src="https://github.com/FGarridoV/resources/blob/main/colab.png?raw=true">
</p>

- **Step 7:** You are all set! You can work on your notebook.

**Notes:**
- The uploaded notebook file will be stored on your Google Drive in the folder My Drive \Colab Notebooks\
- If you close the session and want to get started again, then: Go to [Colab](http://colab.research.google.com), open the uploaded notebook from your Google Drive, and re-do Step 5 and 6.


## Option 2: Local environment (not recommended - limited support)

**Minimal requirements:**
- A Python version installed (3.7 or newer)
- An IPython (notebook) enviroment installed on your computer (Jupyter, VSCode or alternatives)
- Basic skills in virtual enviroments (if you don't what to mix your current dependencies)

### Steps
- **Step 1:** Clone or download this repo to your computer (see **Step 1** on Colab section).
- **Step 2:** Two options: (a) Install dependecies separate from your current Python version; (b) Install dependencies for this notebook in your Python version  (easy way):
  - **Step 2.a (you need some knowledge on venvs):**
    - Create a new virtual environment (venv) and install the `requirements_local.txt` file. (see [venv](https://realpython.com/lessons/creating-virtual-environment/) and [install requirements](https://note.nkmk.me/en/python-pip-install-requirements/))
    - Open the notebook you want to work on (**Step 1**) and run the notebook in the newly created venv.
  - **Step 2.b (easy way):** 
    - Open the Python notebook you want to work on (**Step 1**)
    - Uncomment the line related to using a local set-up and run it (see the figure below).
    - Re-comment the lines to avoid re-installing the dependencies every time you run the notebook.
  <p align="center">
  <img width="600" src="https://github.com/FGarridoV/resources/blob/main/local.png?raw=true">
</p>
