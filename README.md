# My_Q-A_chatBot
It is a project to make a Q&A chat bot which will give ans to a questions base on a story given.
## Data Set:
I used kaggle data set orignaly from facebook BABI data set "https://research.fb.com/downloads/babi/".
in this data set the story,question,answer are given in a list format which is inside a Tuple. so data is a Tuple of a list
first we have given a story ,then a question an answer to the question ere are 10000 questions for training, and 1000 for testing. 
However, we emphasize that the goal is to use as little data as possible to do well on the tasks (i.e. if you can use less than 1000 that’s even better) — and without resorting to engineering task-specific tricks that will not generalize to other tasks, as they may not be of much use subsequently. 
Note that the aim during evaluation is to use the same learner across all tasks to evaluate its skills and capabilities.


I have used a English dataset (working on the Hinglish dataset project) while the orignal dataset is given in two languages hindi(hinglish) and english.
eg.  
1 Mary is in the school., Bill is in the kitchen.
Q 'Is Bill in the bedroom'? 	A 'no'	


2 Bill journeyed to the bedroom. Fred travelled to the cinema.
Q 'Is Bill in the bedroom?' A	'yes'	


3 Fred went back to the park. Bill is either in the school or the office.
Q 'Is Bill in the park?' A	'no'	


4 Mary went to the cinema. Julie is either in the school or the office.
Q 'Is Fred in the park?' 	A 'yes'	


5 Julie is either in the park or the school. Bill went back to the office.
Q 'Is Bill in the office?' A	'yes'


### The architechture 
Architechture use to build the model is base on the "End-To-End Memory Networks" by "Sainbayar Sukhbaatar Dept. of Computer ScienceCourant Institute, New York University sainbar@cs.nyu.edu"
"Arthur Szlam"  "JasonWeston Rob Fergus Facebook AI Research New York faszlam,jase,robfergusg@fb.com"


### Results 
 Model accuracy which i am able to genrate from the english data set after 40 epoch with the 32 batch_size comming out to be around 85% in the training data and 79 to 80 % in testing data set.
 
![Q A_C_result](https://user-images.githubusercontent.com/70006540/142425656-456a6ddc-3713-49fc-be73-92dcdb45efda.PNG)
