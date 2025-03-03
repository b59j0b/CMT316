java c
Assessment Proforma 2024-25 
Key Information 
Module Code 
CMT316 
Module Title Applications of Machine Learning: Natural Language Processing and Computer Vision 
Assessment Title 
Coursework 1 
Assessment Number 
1 of 2 
Assessment Weighting 
50% 
Assessment Limits 
No limit for part 1 (but the answers are expected to be quite brief). Part 2 
involves producing a report of up to 1200 words along with Python script. 
The   Assessment Calendar can be found under ‘Assessment    Feedback’ in the COMSC-ORG-SCHOOL organisation on   Learning Central. This is the single point of truth for   (a) the   hand out date and time, (b) the hand   in date   and   time,   and   (c)   the feedback   return   date   for   all assessments.
Learning Outcomes 
The learning outcomes for this assessment are as follows:
1.      Implement and evaluate machine learning methods to solve   a   given task
2.      Explain the fundamental   principles underlying common machine learning   methods
3.      Choose an appropriate machine learning method   and   data   pre-processing   strategy to   address the needs of a given application setting
4.      Reflect on the importance of data representation for the success of machine   learning   methods
5.      Critically appraise the ethical   implications and societal   risks associated with the   deployment of machine learning methods
6.      Explain the nature, strengths and limitations of an implemented   machine   learning   technique   to   an   audience   of   non-specialists
Submission Instructions 
The coversheet can be found under ‘Assessment    Feedback’ in the COMSC-ORG-   SCHOOL organisation on Learning Central.
All files should be submitted via Learning   Central.    The submission   page   can   be   found   under ‘Assessment    Feedback’ in the CMT316 module on Learning Central.    Your submission should consist of multiple files:
This coursework consists of a portfolio divided into two   parts
-          Part (1) consists of selected homework similar to the   one   handed   in throughout   the course. The final deliverable consists of a single   PDF file,   which may include   methodology, snippets of Python code and solved exercises.
-          Part (2) consists of a machine learning project where   students   implement a   basic   machine learning algorithm for solving a given task. The deliverable is a zip   file with   the code, and a written summary   (up to   1200 words) describing solutions, design choices and a reflection on the main challenges faced   during   development.
Description 
Type 
Name 
Coversheet 
Compulsory 
One PDF (.pdf) file 
Coversheet.pdf 
Part 1 
Compulsory 
One PDF (.pdf) file 
Part1.pdf 
Part 2 
Compulsory 
One ZIP (.zip) file containing the 
Python code 
Part2.zip 
Part 2 
Compulsory One PDF (.pdf) file containing the part 2 report 
Part2.pdf 
Any code submitted will   be run in   Python 3   (Linux) and   must   be   submitted   as   stipulated   in   the instructions above.
Any deviation from the submission instructions above (including the   number and types of   files submitted) may result in a mark   of zero for   the   assessment   or   question   part.
If you are unable to submit your work due to technical difficulties, please submit your work   viae-mailto comsc-submissions@cardiff.ac.ukand   notify   the   module   leader.
Assessment Description In this coursework, students demonstrate their familiarity with the topics covered in the   module via two separate parts with the first part worth 40% and the second   part worth      60%.
Part 1 (40%) 
In   Part   1, students are expected to answer two practical   questions.
1.    Your algorithm gets the following results   in a   classification   experiment.   Please   compute   the precision, recall, f-measure and accuracy *manually* (without the   help of your computer/Python, please provide   all steps and formulas).   Include the   process to get   to   the final   result. (15 points) 
Id 
Prediction 
Gold 
1 
True 
True 
2 
True 
True 
3 
False 
True 
4 
True 
True 
5 
False 
True 
6 
False 
True 
7 
True 
True 
8 
True 
True 
9 
True 
True 
10 
False 
False 
11 
False 
False 
12 
False 
False 
13 
True 
False 
14 
False 
False 
15 
False 
True 
16 
False 
False 
17 
False 
False 
18 
True 
False 
19 
True 
False 
20 
False 
False 
2.    You are given a dataset   (named   “real_estate”) with different   house   properties   (dataset   available in   Learning Central). Your goal   is to train machine learning   models   in the training set to predict the   house price of a   unit area   in the   test set. The   problem   should   be framed as both regression and classification.   For regression, the   house   price   of a unit area is given; for classification, there would   be two labels   (expensive and   not-   expensive) depending on   the house price of a unit   area:   expensive   if   it   is   higher or   equal to 30, and not-expensive   if it   is   lower than 30. 
The task is therefore to train two   machine   learning   models (one   regression   and   another one classification) and check their performance. The student can choose the   models to solve this problem. Write, for each of the   models, the main   Python instructions to train   and   predict the labels (one line each, no   need   to   include   any   data   pr代 写CMT316 Applications of Machine Learning: Natural Language Processing and Computer Vision 2024-25Python
代做程序编程语言eprocessing   instructions   in   the pdf) and the performance in the test set   in   terms   of   Root   Mean   Squared   Error (regression) and accuracy (classification). While you will need to write the full code   to   get   to the results, only these instructions are   required   in the   pdf. (25 points) 
Part 2 (60%) 
In   Part 2, students are provided with a text classification dataset (named   “bbc_news”). The   dataset contains news articles split into five categories: tech, business, sport,   politics   and entertainment. Based on this dataset, students are asked to   preprocess the data,   select features and train and evaluate a machine learning   model   of their choice for classifying news articles. Students should include at least three different features to train their   model,   one of them should be based on some sort of word frequency. Students can   decide the type of frequency (absolute or relative, normalized or not) and text   preprocessing for this mandatory word frequency feature. The remaining two (or more) features can be   chosen freely. Then, students are asked to perform. feature selection to reduce the   dimensionality   of all features. 
Note: Training, development and test sets are not provided.   It   is   up to   the   student to   decide the evaluation protocol and partition (e.g.,   cross-validation   or   pre-defining   a training, development and test set). This should be explained in the report.
Deliverables for this part are the   Python code including all   steps   and   a   report of   up   to 1200 words. The   Python code should include the   Python scripts and a small   README file   with instructions on how to run the   code   in   Linux. Jupyter   notebooks with   clear execution         paths are also accepted. The code should take the dataset set as   input, and   output   the results according to the chosen evaluation protocol. The code will consist of 25% of the      marks for this part (15 points) and the report the   remaining   75% (45 points). The   code      should contain all necessary steps described above: to get the full marks for the code, it should work properly and clearly perform all required steps. The   report   should   include: 
1)    Description of all steps taken in the   process   (preprocessing,   choice of   features,
feature selection and training and testing of the model). This description should   be   such that one could understand all steps without looking at the   code (15 points - The quality of the preprocessing, features and algorithm will not be considered here) 
2)    Justification of all steps. Some   justifications may be   numerical,   in   that   case   a
development set can be included to perform. additional   experiments. (10 points - A reasonable reasoned justification is enough to get half of the marks here. The usage of the development set is required to get full marks) 
3)    Overall performance (accuracy,   macro-averaged   precision,   macro-averaged   recall   and macro-averaged   F1) of the trained model   in the dataset. (10 points - 
Indicating the results, even if very low, is enough to get half of the marks here. A minimum of 65% accuracy computed on a test set of at least 10% of the dataset is required to get full marks) 
4)    Critical reflection of how the   deliverable   could   be   improved   in the future   and   on         possible biases that the deployed machine learning   may   have. (10 points - The depth and correctness of insights related to your deliverable will be assessed) 
The report may include   tables   and/or figures.
Assessment Criteria 
Credit will be awarded against the following criteria. Credit will   be awarded   against the   following   criteria.
➢ Part 1. The main criteria for assessment   is   based   on   the   correctness   of the
answers, for which the process is also required. Full   marks will   be given   for   answers   including both the correct answer and a correct   justification or methodology.
➢ Part 2. This part is divided   into   Python code   (25%)   and   an   essay   (75%).   The   code   will be evaluated based on whether it works or not,   and whether   it   minimally contains the necessary steps required for the completion of Part 2.   Four   items will   be evaluated in the essay, whose weights and descriptions are   indicated   in the assessment instructions. The main criteria to evaluate those items will   be the   adequacy of the answer with respect to what was asked, and the   justification provided.
High 
Distinction 80%+ 
Full understanding of all the concepts, correct answers and 
methodology, well-documented and working code, accurate justification and description of all steps and critical analysis. 
Distinction 70-79% 
Excellent understanding of all the concepts, correct answers and 
methodology, well-documented and working code, accurate justification and description of the steps with critical analysis. 
Merit 
60-69% 
Good understanding of all the concepts, working code, justification and description of steps and analysis. 
Pass 
50-59% 
Few errors in questions and code, methodology with issues and not detailed description of steps and justification or with issues 
Marginal Fail 
40-49% Reasonable attempts to address the problem, but code with clear errors, flawed methodology, incorrect solutions, and lack of clear description of justification of steps. 
Fail 
0-39% 
Code with errors, flawed methodology, incorrect solutions, and no clear description of justification of steps. 




         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
