# project-template
Repository for {game-name}. 

# Links
<!-- Update the below links -->
* [GitHub Pages]()
* [Developer's Journal]()

## Documentation
This repository contains Sphinx code that can be edited, built, and published to a GitHub Pages website. 
See the GitHub Pages for the built results of this documentation. 

## Building the Docs Through GitHub Actions Automation
Merging any non-main branch into main will trigger a GitHub Action that will build and publish the docs to GitHub Pages. 'pages' is the branch that will be published and should not be used for any other reason.

## Building the Docs Locally
The following section provides instructions on how to build the HTML locally. This step is not necessary, but may be useful for a quick preview of what the built HTML will look like.

### Dependencies
#### Python
##### Version
[Python 3.11-64 bit](https://www.python.org/downloads/windows/).

##### Python Package Dependencies
The doc_requirements.txt file contains all Python dependencies needed to build the Sphinx documentation locally. Run the following command in the Documents folder using the desired Python environment:

`pip install -r doc_requirements.txt`

### Build
To build the Sphinx code, run the following command in the root of the project:

`sphinx-build doc _build`

The HTML will be built to _build folder and can be preview by opening the HTML files within.
