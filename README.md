# Using Pandas to compare files

## Table of contents
- [Overview](#overview)
- [Prerequisites](#prereq)
- [Example Code](#examplecode)
- [References](#references)

<div id='overview'/>

## Overview

Exploring Jupyter notebooks will test the validity of using Jupyter to design a real-time reconciliation system.



<div id='prereq'/>

## Prerequisites:

 - Installing PiP

```console
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py`

python get-pip.py --user
```

 - Installing Virtual Environment 
```console
pip install --user virtualenv
```

 - Initialize python3 in new virtual environment
```console
virtualenv -p python3 env
```

 - Activate environment  
```console
. env/bin/activate
```

 - Installing dependencies
```console
pip install -r requirements.txt
```

<div id='examplecode'/>

## Running the notebook 

Run the code
```console
jupyter notebook Exception_Draft.ipynb
```
### What is the Notebook doing?
Comparing:
 - Exploring python
 - Exploring markdown
 - Exploring bash commands 
 - Exploring DataFrames
 - Comparing DataFrames
 - Exploring UI/UX


To stop the virtual session  
```console
deactivate
```


<div id='references'/>

## References
 - [Installing Virtual Environment](https://virtualenv.pypa.io/en/stable/installation/)
 - [Python Data Analysis Library](https://pandas.pydata.org/)
 - [Jupyter Notebook Tutorial](https://www.youtube.com/watch?v=HW29067qVWk&t=417s)