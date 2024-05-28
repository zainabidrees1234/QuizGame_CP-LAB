  QUIZ GAME – READ ME FILE
  
  ************  How to run the files in VS  ************  
  [[[[ First of all download the zip folder QUIZ GAME - ZIP and extraxt it on your device. Then follow further steps ]]]]]
  
1.	Open Visual Studio:  
  
•	Launch Visual Studio on your computer.  
  
2.	Create a New Project:  
  
•	Go to File -> New -> Project.  
•	Select Empty Project under C++.  
•	Name your project (e.g., QuizGame) and click Create.  
  
3.	Add Source File (main.cpp):  
  
•	In the Solution Explorer, right-click on the Source Files folder.  
•	Select Add -> New Item.  
•	Choose C++ File (.cpp), name it main.cpp, and click Add.  
•	Copy the provided main.cpp code and paste it into this file.  
  
4.	Add Text Files (warmup_questions.txt and challenge_questions.txt):  
•	In the Solution Explorer, right-click on the project name (e.g., QuizGame).  
•	Select Add -> New Item.  
•	Choose Text File, name it warmup_questions.txt, and click Add.  
•	Copy the provided warmup_questions.txt content and paste it into this file.  
•	Repeat the same steps to add challenge_questions.txt and paste the respective content.  
  
5.	Set Text Files as Project Resources:  
  
•	Right-click on each text file (warmup_questions.txt and challenge_questions.txt) in the Solution Explorer.    Select Properties.  
•	Ensure Item Type is set to Content and Working Directory is set to project directory(e.g.,$(ProjectDir))  
  
6.	Build and Run the Project:  
•	Click on Build -> Build Solution to compile the code.  
•	After successful compilation, run the project by clicking Debug -> Start Without Debugging or press Ctrl + F5.  
  
Expected Output  
Upon running the project, you should see a console window displaying the main menu with options to start the quiz, view help, reset score, show record, or exit.  
  

**************  Main Menu Options  **************  

  
1.	Start Quiz:  
•	Follow the prompts to enter your name and answer questions in the warm-up and challenge rounds.  
2.	Help:  
•	Displays information on how to play the game.  
3.	Reset Score:  
•	Resets the current score to zero.  
4.	Show Record:  
•	Shows the current score and highest score achieved.  
5.	Exit:  
•	Exits the game.

 
 ********  How to Play the Game  ********
 
  
Start the Game:  
  
•	Choose "Start Quiz" from the main menu.  
•	Enter your name when prompted. 

Answer Questions:  
  
•	Answer multiple-choice questions (A/B/C/D).  
•	Qualify for the Challenge Round by answering at least 2 out of 3 warm-up questions correctly.  
  
Challenge Round:  
  
•	Answer up to 7 questions for higher scores.  

Other Options:  
  
•	View instructions in "Help".  
•	Reset your score with "Reset Score".  
•	Check your "Show Record" for current and highest scores.  




------------------*************-------------------
   
