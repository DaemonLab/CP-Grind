# CP-Grind

## Description
Create an application that allows the user to create a room and invite his friends of similar skill level. This application uses the Codeforces ratings of the users to create a single list of questions having similar difficulties. Each of the participant then clicks on the Codeforces links and start solving the questions. The one who completes them quicker wins.

## Specifications

### User
1. Firstly, all the users need to register and provide their Codeforces ID while registering.
1. A user can create a room and share its link with his friends, who can then join the room using that link.
1. The participant then gets a list of questions and starts solving them one by one on Codeforces.
1. Once he has solved a question on Codeforces, he needs to refresh the page and check his progress.
1. The room ends, once a participant has solved all the questions.

### Server
1. It contains a database for signng in the users and storing their Codeforces IDs.
1. It creates a room and generates a sharable link.
1. Generate a list of common questions for all the users within the room and sorts them from easiest to hardest.
1. As soon as the user refreshes the website, he can see the number of questions he has completed.
1. Once, a user has answered all the questions, the room ends and others can see their progress.
