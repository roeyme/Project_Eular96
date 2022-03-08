# Project_Eular96
This project contains 3 classes and 2 toolboxes.

Classes:

BoardState - This class is a toolbox that provides an efficient and transparent
analysis of soduko boards, including executing basic actions. 
It is used to efficiently and easily implementing soduko solvers,
in addition to partially unify the implementation of different solvers.

SodukoSolver - This class is not accessed by the end-user and provides
a toolbox of soduko solvers that use the 'boardAnalyzer' module

BoardsManager - This class is used direclty by the end-user.
It handles reading, solving, storing and displaying
Soduko boards.


Toolboxex:

'Toolbox.py' - This module provides general auxaliry methods.

'SodukoTester.py' - This module provides a toolbox to check solutions of soduko boards.
