# Student-Grading-System
</br>
</br>
</br>
Write a program to allow the academic staff to enter the coursework marks and final marks for
the students. The program reads scores in three categories: test, assignments and final. Each
category is weighted: its points are scaled up to a fraction of the 100 percent grade for the
course. As the program begins reading each category, it first prompts for the category's weight.
The user begins by entering student id and name follows by the scores earned on test. The
program asks whether test scores were shifted, interpreting an answer of 1 to mean “yes” and
2 to mean “no.” If there is a shift, the program prompts for the shift amount, and the shift is
added to the user's test score. Exam scores are capped at a max of 100; for example, if the user
got 95 and there was a shift of 10, the score to use would be 100. The midterm's “weighted
score” is printed, which is equal to the user's score multiplied by the exam's weight. Next, the
program prompts for data about the final. The behavior for each is the same as the behavior
for test.
