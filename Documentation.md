# 1) Overview
Accio Songs is a search engine tool tailored to musically inclined individuals. This tool allows for query by Track, Artist, Album, or Lyric.

# 2) Implementation

Accio Songs is implemented using Flask, Python, and HTML. The webpages use a combination of HTML, Javascript, and CSS. The search results are powered by a deployment of Elastic App Search which work with various API clients to provide the queried data.

# 3) Usage

## Installation

#### If python has already been installed:

Open CMD, Bash, or Terminal

Then type ```python --version```

Ensure this is a current version of python3


#### If installation is required, visit [python.org](https://www.python.org/downloads/).

## Setting up the Virtual Environment

Change the directory the project folder.

```
cd ...../accio-songs-search
```

Then initialize a New Python environment.

```
python3 -m venv /path/to/new/virtual/environment    
```

## Activating VEnv and Installing the Dependencies
To assist activating the Virtual environment and installation of dependencies below bash script is provided:

    ./setup.sh

## Running Elastic Search and Elastic App Search
Run the following 2 files in separate terminals to run an Instance of Elastic Search and Elastic App Search:

    ./run-elastic.sh
    ./run-app-search.sh

# 4) Contributions
Kushagara Soni
Virginia Atieh

1) An overview of the function of the code (i.e., what it does and what it can be used for). 
2) Documentation of how the software is implemented with sufficient detail so that others can have a basic understanding of your code for future extension or any further improvement. 
3) Documentation of the usage of the software including either documentation of usages of APIs or detailed instructions on how to install and run a software, whichever is applicable. 
5) Brief description of contribution of each team member in case of a multi-person team. 
