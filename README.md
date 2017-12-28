# libroute-stack
A deployment stack for the libroute application - a framework for scientific, engineering and compute applications

## Overview
This repository contains the libroute stack containing the following components:

 - libroute application
 - nginx (to serve results files over http)
 - dind (an instance of the docker api)

## Installation
To run the application, clone the libroute repository as follows:

```
git clone https://github.com/libroute/libroute-stack
```

Then from inside the libroute-stack directory, build and launch the docker applications using:

```
docker-compose up -d
```

Navigate to http://localhost:3000 to use the libroute application

## Documentation
Visit [libroute.io](https://libroute.io) for full documentation
