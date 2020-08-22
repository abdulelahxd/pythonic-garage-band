# Pythonic Garage Band

**Author**: abdulelah
**Version**: 1.0.1

## Overview
Program which uses Python classes to model a Band made up of different kinds of musicians like Guitarist,Bassist, and Drummer. Musician base class used to handle common functionality which particular kinds of musicians will inherit.


## Getting Started
1. In terminal navigate to the folder with the test_band.py.
2. Run command "pytest-watch".


## Architecture
* Python 3.8.2
* Pytest
* Pytest-watch


## workflow
1. class Musician: creates instances of the Musicians
2. class Guitarist(Musician):  inherits properties of Musician class
3. class Bassist(Musician): inherits properties of Musician class
4. class Drummer(Musician): inherits properties of Musician class
5. class Band: creates instances of the Band from the provided data_file
