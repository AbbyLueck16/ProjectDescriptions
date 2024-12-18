# ProjectDescriptions
This repository discusses the projects found within my GitHub that showcase some assignments I completed during my time studying Computer Science at the University of St. Thomas. These projects were parts of various classes, including Computer Architecture, Object Oriented Design and Programming, and Advanced Information Security. 

## Project One: MIPSfactorial
https://github.com/AbbyLueck16/MIPSfactorial<br>
***This assignment was completed for CISC 340, computer architecture with Professor Lamb***<br>
The purpose of this assignment was to implement my knowledge of recursion from previous courses and see how the code is stored in registers in MIPS assembly. This program calculates the factorial of an integer given by the user using a recursive approach. While the program was relatively simple, this project taught me about stack management and how registers are used in assembly language.


## Project Two: HashCollisionProject
https://github.com/AbbyLueck16/HashCollisionProject<br>
***This assignment was completed for CISC 410, advanced information security with Dr. Yilek***<br>
This assignment was intended to illustrate how a "malicious" user can trick somebody into signing a message that was altered. This assignment used the scenario of a personal assistant writing an email for her boss, who will sign it once completed. The personal assistant then is to find another message (with malicious meaning) that when signed hashes to the same as the original message. This then can be sent to the recipient with the correct signature from the boss but with a harmful altered message. 

Through doing this assignment I learned that without careful encryption techniques, malicious users can corrupt and impersonate others in messages. This problem illustrates the importance of cryptographic techniques to ensure message integrity and authenticity.

# Project Three: ElectionResult 
https://github.com/AbbyLueck16/Electionresult<br>
***This assignment was completed for CISC 230, object oriented design and programming with Professor Akram***<br>
This program calculates the result of an election based on the number of votes each candidate received in various "areas" as provided by user input.

This assignment was completed during one of my earlier computer science classes, so while it is not particularly complex, it address an important real-world context. Elections are fundamental piece of United States democracy. Elections empower the public by allowing them to vote upon their elected officials. For instance, presidential elections involve citizens voting within their states, each state declaring a winner and contributing a set number of electoral votes towards the overall election results. 

This program loosely simulates this process. It prompts the user if they would like to process an "area" which can represent a state in a real election. The user enters the number of votes each candidate received in that area, and the program calculates which candidate won the area. After all areas are processed, the program displays the overall winner of the election and the number of areas won by each candidate.

The main difference between this program and a real election is how areas contribute to the overall results. In this program, each area is treated equally, whereas in a real election each area gets a different amount of votes based on population size. 

This program could be modified to ask more specific questions, such as which area is being entered, and use that information to calculate electoral vote counts. With these modifications we can create a more realistic election simulation. Nonetheless, this program gives a basic example of one of the fundamental processes of United States democracy. 
