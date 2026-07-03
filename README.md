# UKCEH Summer School - Data Driven Approaches to Hydrological Science
[![Binder](https://gesis.mybinder.org/badge_logo.svg)](https://gesis.mybinder.org/v2/gh/NERC-CEH/UKCEH_Summer_School/main)

Welcome to the **UKCEH Summer School** 2026 on *Data Driven Approaches to Hydrological Science*. 

![Project_logos.png](https://raw.githubusercontent.com/NERC-CEH/UKCEH_Summer_School/refs/heads/main/content/Project_logos.png)

This series of hands-on workshops introduces the fundamentals of accessing, modelling, and analysing hydrological data and approaches. Each session is designed to build practical skills through guided exercises and additional resources. Below you will find brief summaries of each workshop, along with links to the corresponding resources that we will explore together during the training.

<details>
    <summary><i><b>If you are not attending the online Summer School, please click here to read this message.</i></b></b></summary>
    
These notebooks were developed for the UKCEH Summer School and are intended for interactive use during the training sessions. They are designed to run on any JupyterLab environment, such as <a href=https://colab.google/>Google Colab</a>, which allows you to get started quickly without any local setup. You can also launch the repository using <a href="https://mybinder.org/">Binder</a> by clicking the <a href="https://gesis.mybinder.org/v2/gh/NERC-CEH/UKCEH_Summer_School/main">Binder launch badge</a>, at the top of this README, which will open the repository in a JupyterLab environment. The Binder environment is pre-configured with the necessary Python packages from the environment file (requirements.txt). For guidance on how to run the notebooks, see the [Running the Training Notebooks](#running-notebooks) section below.

*Note: Collab and Binder has resource limitations, so there might be some performance issues.*

You are also very welcome to explore the notebooks at your own pace, on any platform of your choice, as long as the required packages are installed. This repository includes a requirements.txt file listing all the necessary dependencies for the various workshops. To install these locally, run the following command:

   > !python -m pip install -r requirements.txt

If you would like help setting up the environment on your local machine or another platform, we are happy to provide support. 

</details>

---

## Training Objectives
The high-level objectives of this summer school are:
- Introduce fundamental concepts in water resources modelling
- Demonstrate how to access and work with remote datasets using Python
- Provide an overview of key datasets commonly used in hydrological science
- Offer hands-on experience with standard tools and packages through practical applications

<a id='running-on-colab'></a>
## Running the Training Notebooks
#### To run the training notebooks using *Google Colab*, follow these steps:
1. **Log in to your Google account** and open [Google Colab](https://colab.research.google.com/).
2. In Colab, go to **File > Open notebook**.
3. Select the **GitHub** tab.
4. Paste the URL of the specific notebook (ending in `.ipynb`) from this repository into the search bar.
5. Click on the notebook you want to open.

> **Important:** Before you start editing, make sure to **Save a copy to your own Google Drive**.

6. Go to **File > Save a copy in Drive**. This will open a new tab with the title **Copy of <Notebook Name>**.
7. You are now working on your own copy of the notebook, which you can rename if you choose.
8. You can safely close the original (read-only) notebook tab and continue working on your personal copy.
9. The copied notebook will be saved in your Google Drive and can be accessed anytime.

#### To run the training notebooks using *Binder*, follow these steps:
1. To open the GitHub repository in Binder, follow *one* of the options below:
	- *Launch directly from GitHub*: Click the **Launch Binder** badge at the top of README document (or use the <a href=https://gesis.mybinder.org/v2/gh/NERC-CEH/UKCEH_Summer_School/main>Binder link</a> here.
	- *Launch via the Binder website*: Open https://mybinder.org/. Enter the <a href=https://github.com/NERC-CEH/UKCEH_Summer_School/tree/main>GitHub repository URL</a> under **GitHub repository name or URL**. Leave *Git ref* and *File to open* blank to open the full repository. Click **Launch**.
2. Wait for Binder to build and start the interactive environment. This may take several minutes the first time the repository is launched.
3. Once the Jupyter environment opens, navigate to the notebook directory and select the training notebook you wish to run.
4. Any changes made in the Binder session are temporary and will not be saved to the GitHub repository.

> **Important:** Before closing the session, make sure to **Download a copy of your Notebook**.

5. Download the notebook using **File > Download As > Notebook (.ipynb)** before ending the session.
6. Binder sessions are temporary and may terminate after a period of inactivity.

---

## Introduction to the Workshops
This series of different interactive workshops is designed to introduce participants to data-driven approaches in hydrological science. Each session focuses on a specific aspect of working with hydrological data, from modelling concepts to accessing, exploring, and applying datasets in research contexts.

### Workshop 1: Intro to Git
**Facilitators:** *Simon Stanley*

This workshop will have hands-on Git exercises designed to help you practise essential version control skills. It looks at common workflows such as commiting, branching and merging, as well as touching on the use of remote repositories. The GitHub repo used for this workshop is in [Workshop 1](https://github.com/NERC-CEH/UKCEH_Summer_School/blob/main/Workshop_1).

### Workshop 2: Approaches to Hydrological Modelling
**Facilitators:** *Helen Baron | Giovanni Bernardi | Zara Crapper | Nathan Rickards*

An introduction to hydrological modelling, with a hands on application of a UKCEH water resources model in a case study catchment. Here is the link to [Workshop 2](https://github.com/NERC-CEH/UKCEH_Summer_School/blob/main/Workshop_2).


### Workshop 3: Exploring hydrological data
**Facilitators:** *Matt Dalle Piagge | Tom Keel | Kit Macleod*

Hands-on session on exploring different types of hydroclimate datasets, including basic techniques for processing, visualisation, and analysis. Here is the link to [Workshop 3](https://github.com/NERC-CEH/UKCEH_Summer_School/tree/main/Workshop_3).


### Workshop 4: Researching with hydrological data
**Facilitators:** *Tom Keel | Matt Dalle Piagge | Kit Macleod*

Do it yourself session with guidance on using hydrological data into research workflows, with a focus on applications and good data practices. Here is the link to [Workshop 4](https://github.com/NERC-CEH/UKCEH_Summer_School/tree/main/Workshop_4).


### Workshop 5: Creating FAIR Outputs
**Facilitators:** *Jasmine Hunter | Els Dhiedt*

During this session you will gain an understanding of the FAIR principles, how to create and publish FAIR data, and discuss the importance of open science through a series of group exercises. Here is the link to [Workshop 5](https://github.com/NERC-CEH/UKCEH_Summer_School/tree/main/Workshop_5).


### Workshop 6: Using an open dataset and machine learning to explore British hydrological diversity
**Facilitators:** *Molly Asher | Ali Rudd | Matt Fry*

This workshop introduces the CAMELS-GB dataset and how it can be used to better understand, explain and predict how catchments are likely to respond to rainfall events. We explore how maps can be used to visualise and reveal patterns in catchment characteristics and then use machine learning techniques to investigate how catchment characteristics influence hydrological behaviour and flow variability across Great Britain. Here is the link to [Workshop 6](https://github.com/NERC-CEH/UKCEH_Summer_School/tree/main/Workshop_6).

---

## Contact
If you have any questions or need assistance with the workshops, please feel free to get in touch with us:

> [Amulya Chevuturi](mailto:amuche@ceh.ac.uk)  
> [Matt Dalle Piage](mailto:matbro@ceh.ac.uk)  
> [Tom Keel](mailto:tomkee@ceh.ac.uk)  
> [Nathan Rickards](mailto:natric@ceh.ac.uk)

