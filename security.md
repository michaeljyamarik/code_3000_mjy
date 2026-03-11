
Homework 5:
-> The intended user of this code is me. (And maybe gradescope and the professor)

-> Not really any concerns if the code fell into the wrong hands. I haven't put anything sensitive or persoonal in here (because I haven't done the homeworks) so the only thing that would be a problem, is if someone stole the assignments in here and tried to use them for their own assignments, or maybe to cheat. But thats not really my problem.

-> Here are some steps

|
+-> the .gitignore is a good touch, but I didn't add that. Those can be used to store certain information to use in the github (like API keys and such) that don't get uploaded to the github

|
+-> I added a branch protection for main that requires a pull_request approval in order to push to main. This way I am only putting information I know is secure and correct on the main branch

|
+-> I set up my CODEOWNERS file on my dev branch for Github to be for me only