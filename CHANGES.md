#To-Do List:
- Some form of database for recipes
- Consolidate recipe ingredients for multiple recipes
- Other Wit story types
- Search function
- Song sender
- News filter
- Praw/reddit module?
- Help option
- Google places other requests? Maybe keyword search

#V6.7
- Added google places api support
- Added "What restaurants?" request
- Can recieve and store locaiton data for at least 30 min?

#V6.6
- Splits up larger messages to fit messenger char limit
- Working on search function
- Checks if recieved messages are part of story sets, otherwise asks for a rephrase

#V6.5
- Eliza.py added
- Basically just reflects questions, not bad
- Working on weather request next

#V6.4
- Memory leak issues with aiml bot.
- Trying a different chat bot approach later
- Implementing weather

#V6.3
- Attempting to add A.L.I.C.E to the fb bot
- Need to find a way to loop responses inside event handling for the aiml bot
- Solved above, needed to set a flag to get around normal event handling

#V6.2
- Scrapped the Wit.ai run_actions section
- 500 errors from somewhere
- Fixed infinite hi
- FB messages are limited to 320 chars
- Limited to ingredients of one recipe
- Recipe ingredient requests now work
- Lxml since python parser is not working for bs4

#V6.1
- Facebook support now works (It can connect and send/recieve messages)
- Infinite loop on greetings from wit.ai
- Page chat only so the bot is stuck with single chat
- Basis for the bot server came from hult's flask-python chatbot

#V6
- Removing pygooglevoice
- Attempting to use flask to create a fb messenger bot
- Removed weather command support 

#V5
- Can use wit to determine what type of response is required
- Can run methods from recieved messages
- Response times vary and pygooglevoice encounters parsing errors
