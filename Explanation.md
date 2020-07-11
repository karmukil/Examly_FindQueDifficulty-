# Examly_FindQueDifficulty-
About the project:
The project is implemented in c++.The reason for choosing c++ is,c++ is the fastest programming language with expansive built_in functions.To find the difficulty of 
the given question the following algorithm is used

Simple Pseudocode
difficulty_of_the_que=(difficulty_based_on_total questions_correct * 60) / 100 +
               difficulty_based_on_manual_entry * 20/100 +
               difficulty_based_on_queChanged * 2/100 +
               difficulty_based_on_queType * 18/100;

Various factors affect the difficulty of question.Total number of correct and wrong answers contributes 60% in finding the difficulty of the particular question.The feedback of the
the question contributes 20%.Number of times the question changed ,the program is compiled,hints used contributes 2%.The type of the question(mcq,fillup,programming) contributes
18% in finding the difficulty of the question.
STL container(unordered_map) is used to store the data.unordered_map uses hash to store the data.Thus retrieval of the data taken O(1) time complexity.Calculating the difficulty 
takes O(N) time complexity.Where N is the number of questions.
               
