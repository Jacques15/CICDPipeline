# Heroku2
Flask website that uses Travis CI for a unit test and deploys to Heroku. The code is sent to Sonarscanner for static code analysis. 
The website removes punctuation (Every character not a letter or number) from user input and outputs the new string. Travis CI performs
a single unit test (pytest) on the code by testing the punctuation removing function.
