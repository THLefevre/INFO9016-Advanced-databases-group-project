# INFO9016-Advanced-databases-group-project
Repository for the projects of the INFO9016 - Advanced databases course.

## Overview
This repository contains two assignments completed for the INFO9016 – Advanced Databases course at the University of Liège. Each assignment is a self-contained Jupyter notebook tutorial introducing a database technology to readers with a background in relational databases, built around a running example.

### Geospatial queries with MongoDB (`Tutorial_GeoSpatialQueries_MongoDB.ipynb`)
A tutorial on MongoDB's geospatial capabilities, using OpenStreetMap data (benches, cycle paths and parks in Brussels) retrieved through the Overpass API.

### Assignment 4 – Using Prolog to query databases (`Project_TutorialProlog.ipynb`)
A tutorial accompanying a 1-hour lecture given as part of the course project, extending the lecture's content. Using SWI-Prolog through PySwip and a Pokémon knowledge base built from PokéAPI, it covers:
- Facts, rules, unification and backtracking, compared with Datalog
- Recursion, lists, cuts (green vs red) and negation as failure
- Tabling, modules and constraint programming with CLP(FD)
- A simulated team battle combining these mechanisms

### Requirements
- MongoDB tutorial: Docker, Python 3.8+, `pymongo`, `requests`, `shapely`
- Prolog tutorial: SWI-Prolog, Python 3, `pyswip`

## Authors
These projects were carried by:
- [Alexandre Dutailly](https://github.com/Hyarx)
- [Thibaut Lefèvre](https://github.com/THLefevre)
