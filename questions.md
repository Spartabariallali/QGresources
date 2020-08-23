# Answering DevOps related Questions

## TDD?
- TDD stands for test driven development. It is a process usually employed developers when producing their code in the development stage. In short, as developers code new functionalities and additions to the code they employ unit testing to verify/validate the outcome of that functionality. Unit testing is the act of testing code at a microlevel and specifically what I mean is individual code blocks such as functions or classes.
## How have I employed TDD?
- I have employed TDD when undertaking a python software development project. The Aim of the project was to create a user interface that can be used by an airport employee. The UI needed to have some basic functionality such as being able to take customer bookings meaning retaining the customer's information as well as have the ability to log into another system where the correct employ could reassign planes onto a specific flight plan.
To ensure TDD was employed in this process I created an a file alongside my main.py file which included the modules pytest and unittest. I would then assert_equal with every function that I created in the code to ensure its outcome was accurate. 
