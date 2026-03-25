This is an export of most of the variables accessible by velo made more searchable by mkdocs.

TODO:
    - Find better formatting for all of the data and add it to the script.
    - Add a way to attach documentation to a variable.
    - Add a way to merge new scans with the previous scans and documentation.


[!Note]
    This is a placeholder from the SR-Wiki, It doesn't include the script for iterating over fields in-game.

## Building the project locally

The wiki is created by making [markdown](https://www.markdownguide.org/getting-started/) files and [material](https://squidfunk.github.io/mkdocs-material/) for [mkdocs](https://www.mkdocs.org/) turning them into webpages. Instructions for if you wanted to build it locally for some reason:

> [!Note]  
> This assumes you already have python installed and have familiarity with the terminal.

Clone the repository.  
``git clone https://github.com/StarFilledSky/Velo-Docs``  

Create a python virtual environment in the directory.  
``python -m venv venv``  

Activating the virtual enviroment.  
Windows  
``./venv/Scripts/Activate.ps1``  
Linux / MacOS  
source myvenv/bin/activate``

Install the requirements for building the project.  
``pip install -r requirements.txt``

You can now edit files in the src/ directory and use `mkdocs build` to generate files in the docs/ directory and `mkdocs serve` if you wanted to view the files served from a local webserver.