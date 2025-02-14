[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)

[![deploy-book](https://github.com/aronwalsh/MLforMaterials/actions/workflows/deploy.yml/badge.svg)](https://github.com/aronwalsh/MLforMaterials/actions/workflows/deploy.yml)
[![made-with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](http://commonmark.org)
[![CC-BY license](https://img.shields.io/badge/License-CC--BY-blue.svg)](https://creativecommons.org/licenses/by/4.0)

# Machine Learning for Materials

Online resource of a practical machine learning course in the Department of Materials at Imperial College London.

You have the option to browse the files or download the complete folder using the green `clone or download` button on the top right of the screen ([zip file](https://github.com/aronwalsh/MLforMaterials/archive/master.zip)).

## Course Description

_Machine Learning for Materials_ (MATE70026) provides an introduction to statistical research tools for materials theory and simulation. It is aimed at senior undergraduate or junior postgraduate students. 

You will consider how composition-structure-property information in materials science can be represented in a form suitable for machine learning. You will then build, train, and evaluate your own models using public tools and open datasets. 

A hybrid teaching style will be followed with a mixture of lectures and assignments. The course assumes a basic working knowledge of the Python 3 programming language.

[Lecture Slides](./slides)

[Post a Query](https://github.com/aronwalsh/MLforMaterials/issues)

## Course Website

You can view the site at [https://aronwalsh.github.io/MLforMaterials](https://aronwalsh.github.io/MLforMaterials)

To build a local copy, first install [Jupyter Book](https://jupyterbook.org):

`pip install -U jupyter-book`

then enter the repository and run 

`jupyter-book build .`

## Acknowledgements

This module was developed by Aron Walsh with the assistance of [Anthony Onwuli](https://github.com/AntObi) and [Zhenzhu Li](https://github.com/lizhenzhupearl).


## Pulling Upstream Changes

Note to self on how to pull down new coursework notebook each lecture.

Setup for new git env:

    git remote add upstream https://github.com/aronwalsh/MLforMaterials

    git remote --verbose

Pulling each change:

    git fetch upstream

    git branch --all

    git merge upstream/2025 main

Checking out last year's notebooks:

    git checkout upstream/2024