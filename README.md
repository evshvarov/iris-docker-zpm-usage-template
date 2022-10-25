## iris-docker-zpm-template
This is a template for repositories where you need a docker image that takes vanilla InterSystems IRIS Community Edition image with ZPM Package Manager inside and installs a package.
The template goes also with a few files which let you immedietly compile your ObjecScript files in InterSystems IRIS Community Edition in a docker container

[![Gitter](https://img.shields.io/badge/Available%20on-Intersystems%20Open%20Exchange-00b2a9.svg)](https://openexchange.intersystems.com/package/iris-docker-zpm-template)
 [![Quality Gate Status](https://community.objectscriptquality.com/api/project_badges/measure?project=intersystems_iris_community%2Fcsvgen&metric=alert_status)](https://community.objectscriptquality.com/dashboard?id=intersystems_iris_community%2Fcsvgen)
 <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/evshvarov/csvgen">


## Prerequisites
Make sure you have [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and [Docker desktop](https://www.docker.com/products/docker-desktop) installed.

## Installation 

Clone/git pull the repo into any local directory

```
$ git clone https://github.com/intersystems-community/objectscript-docker-template.git
```

Open the terminal in this directory and run:

```
$ docker-compose build
```

3. Run the IRIS container with your project:

```
$ docker-compose up -d
```


## How to Use it
This repository is a way to get a new container image with IRIS and one-two-many arbitrary zpm packages installed.
Change csvgen package in [this line](https://github.com/intersystems-community/iris-docker-zpm-usage-template/blob/01a8734b89d56643e4f53372df43e620d5b5c2b3/iris.script#L10) to a package you need and build the image again.



