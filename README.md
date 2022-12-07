# Early-Warning-System
DATA1030 academic early warning system

The project consists of the elaboration of an academic early warning system that signals potential academic issues early-on, in order to correct them.

This src folder contains six notebooks: three focusing on XGboost and three focusing on all the other models we used. 

Because grade information features arrive as the semester progresses, a new set of models must be re-trained when grades arrive. 
Grades arrive twice in the semester: so there are three main intervals of time that are of interest: before grade/scores info arrive, 
after first grade/scores info arrives, and after second grade/scores info arrives. 
This is why there are three notebooks for our pipeline, and three notebooks for our separate XGboost implementation.

In total there are seven models trained in three different time intervals, totaling 21 distinct models across all six notebooks.

At prediction time, it is necessary to select a model that is trained on the available features. 

CODING ENVIRONMENT:
A yaml file has been provided so that the python environment used can be reproduced. Package versions are as specified in the yaml file.
