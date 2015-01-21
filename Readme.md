* Application organization tools

This repository contains tools and scripts to manage our application repository.

** Application repository structure

Check out the wiki: https://github.com/nesi/app-org/wiki

** app-org.py

A script to auto-generate documentation pages for applications installed on one or more clusters, using the application repository structure outlined above.

More info ( for old, java based application: https://wiki.auckland.ac.nz/pages/viewpage.action?title=Application+documention+generation&spaceKey=CERES )

*** Requirements

    pip install click
    pip install --pre airspeed

*** Installing

    cd app-org
    pip install --editable .

*** Running

    app-org --help

