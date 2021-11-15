# Lab 8 - Starter
1) In your own words: Where would you fit your automated tests in your Recipe project development pipeline?
   1) Within a Github action that runs whenever code is pushed 

2) Would you use an end to end test to check if a function is returning the correct output?
   1) no

3) Would you use a unit test to test the “message” feature of a messaging application? Why or why not? For this question, assume the “message” feature allows a user to write and send a message to another user.
 NO. because in this situation you care about flow. therefore you would use end to end testing.

 4) Would you use a unit test to test the “max message length” feature of a messaging application? Why or why not? For this question, assume the “max message length” feature prevents the user from typing more than 80 characters.

yes because unit testing is perfect for verifiying outputs and this is what this feature really needs.