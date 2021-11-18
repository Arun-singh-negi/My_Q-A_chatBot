# My_Q-A_chatBot
It is a project to make a Q&A chat bot which will give ans to a questions base on a story given.
## Data Set:
I used kaggle data set orignaly from facebook BABI data set "https://research.fb.com/downloads/babi/".
in this data set the story,question,answer are given in a list format which is inside a Tuple. so data is a Tuple of a list
first we have given a story ,then a question an answer to the question ere are 1000 questions for training, and 1000 for testing. 
However, we emphasize that the goal is to use as little data as possible to do well on the tasks (i.e. if you can use less than 1000 that’s even better) — and without resorting to engineering task-specific tricks that will not generalize to other tasks, as they may not be of much use subsequently. 
Note that the aim during evaluation is to use the same learner across all tasks to evaluate its skills and capabilities.


I have used a English dataset (working on the Hinglish dataset project) while the orignal dataset is given in two languages hindi(hinglish) and english.
### The architechture 
Architechture use to build the model is base on the "End-To-End Memory Networks" by "Sainbayar Sukhbaatar Dept. of Computer ScienceCourant Institute, New York University sainbar@cs.nyu.edu"
"Arthur Szlam"  "JasonWeston Rob Fergus Facebook AI Research New York faszlam,jase,robfergusg@fb.com"
