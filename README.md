# OnlineTester
This repository service as a demo landing page for the Online Tester. 

The Online Tester is an educational website for java code unit testing and grading automation as part of the TDD process.

## License
You are NOT permitted to use this code. Please contact me directly if you have any thoughts.

This is not the original repository, and is just a landing page to demo the actual project.

## The story
The website has been decommissioned years ago when I left my job as an instructor at Faculty of Engineering, Alexandria University and came to the states. However, the codebase for the Online Tester is well maintained in a private repository and shared with the teaching staff in case if they want to start using it again.

## How does it work
Online Tester was mainly used to serve as a platform where students can use it to upload their programming assignments, and get the grading right away. 

Usually the student will upload his work to his/her private repository, which is shared with the Online Tester parent account. Then, the student can login to the Online Tester and select his code to start testing it online against some hidden test cases. Finally, he/she will get grading score for his/her work.


### Student working steps
To achieve the TDD paradigm and help the student to understand it, some interfaces and test cases will be shared with them.

1. The assignment description will be sent on Piazza, and it will include the required interfaces and some test cases.
2. The student will need to start solving the problem by using the provided test cases first, then he/she should write additional test cases (Integration, Smoke, and Sanity) to test the interface provided.
3. After the student finishes developing the code, he/she should test it locally against the provided test cases and his/her own test cases too.
4. The student shall upload his code to his/her private repository.
5. The student will login to the Online Tester to submit his code and validate it against some hidden test cases.
6. The student will receive his/her own score.
7. After the deadline, submission won't be available and a grading page will open to show all the grades.

## What are the technologies used
Java, JSP, Threads Programming, Dynamic Compilation, Reflection, JUnit, Tomcat, and AWS.

## What are the features
- It teaches the student how to develope in a TDD paradigm.
- It teaches the student how to work under a contract, which is achieved by coding to an interface.
- The online Tester will verify the student coding style too using the clean code principles.
- The Online Tester will do plagiarism check to prevent cheating.
- The Online Tester shows the compilation or runtime errors to the student, so he/she can debug the issue locally and resubmit their code.
- The Online Tester shows some statistics.
- The Online Tester shows grading page with all of the student work during the semester.
