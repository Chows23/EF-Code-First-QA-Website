# EF-Code-First-QA-Website

For this project it was created with the `C#` with `OOP` and interacting `MSSQL` with a `EF Code First` approach. 
The programs used back-end skills include Microsoft Visual Studio and Microsoft SQL Server Management Studio. 

create a QA (Question and Answer) website similar to StackOverflow, where users
can ask and answer questions.

The system should include the following:
- A main page which contains a list of recent questions, each 10 questions
appear together `pagination`, then the next page contains the next 10
questions…etc.
- Users should be able to post a question. 
- Users should be able to answer a question.
- Each question has a tag, when users click on a tag, they should be
directed to a page containing all the questions related to this tag.
- Each question page starts with the title of the question, the body
(description), the tags, then a list of answers, Users can also comment on
questions and answers.
- Users can sort the questions based on:
o Newest first
o Most answered first
- Each question and answer can have a number of votes, where users can
either upvote or downvote them, users can’t vote on their own questions
and answers.
- Each user has a reputation that appears next to their name, each time a
user gets an upvote they get 5 reputations, a downvote removes 5
reputations.
