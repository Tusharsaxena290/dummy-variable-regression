# dummy-variable-regression
Learning, how dummy variables can be implemented in a model.

So,we have considered attendance as a dummy variable in a model where we astimate GPA considering the SAT score  and the attendnce of the candidate.

i.e to see how is GPA id effected by attendance and SAT score.

If the candidate has covered the minimum 75 percent of attendance, what's going to be effect on the gpa is to be determined.

From the OLS regression results we found out the coffecients. 

We devided the model into two sub models, i.e candidtate has passed the criteria of minimum attendance of 75 percent
and the other one complememtry of that.

so regression is as follows:
 
 GPA=0.6439+0.0014*SAT   -> NO,attendance criteria not full filled.
 
 GPA=0.8665+0.0014*SAT -> YES,attendance criteria is full filled.

