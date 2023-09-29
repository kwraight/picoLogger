# picoLogger

Use picoLogger raw data to derive QC values for upload to ITk Production Database
- example file
- python based notebooks

requirements:
 - pandas
 - altair

---

## Overview

example file: 
 - picoLogger raw data format

notebooks:
 - python based jupyter notebooks for analysing picoLogger data

---

## Running picoLogger converter 

These instructions are for running the converter. To develop the code see [below](#repository-set-up-for-development).

### Notebook

1. clone the repository
> git clone REPOSITORY_LINK
    - obtain the (https) link from the **<> Code** button

2. open notebooks/readData_pico.ipynb
    - edit _User Settings_ section
    - run

3. Use output _csv_ file to upload via script or webApp
    - webApp example: [streamlit](https://itk-pdb-webapps-pixels.web.cern.ch)
        - _genericApp_ theme, _Multi Test_ page

---

## Repository set-up for development

These instructions are to develop the code. To run the converter see [above](#running-picologger-converter).

To set-up repository from the command line:

1. clone the repository
> git clone REPOSITORY_LINK
    - obtain the (https) link from the **<> Code** button

2. make new branch
> git branch NEW_BRANCH_NAME

3. change to new branch
> git checkout NEW_BRANCH_NAME

4. make changes
- _Up to the user_

5. commit to local repository
> git add .
    - adds all changes to be committed
> git commit -m "SOME COMMENT"
    - commits all changes

6. push to remote repository (once you have access to repository)
 - __TO DO__

 ---

## Running notebooks

Run in development environment e.g.: Visual Studio or jupyter

Perhaps relevant example [here](https://github.com/kwraight/msci-simulation/blob/main/notebooks/some_instructions.ipynb) 
