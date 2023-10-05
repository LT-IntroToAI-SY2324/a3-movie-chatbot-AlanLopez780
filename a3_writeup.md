# Assignment 3 - Writeup

Assignment 3 is all about creating this natural language query system.  In order to do so, you have to write a lot of functions to retrieve infomation.  You will also have to write a function to return answers from a pattern-action list.  There is a lot of work to accomplish in this assignment, but this portion is intended for you to write about what you accomplished.

## Reflection Questions
1. In your own words describe the `search_pa_list` function.
The `search_pa_list` function takes a source and loops through a series of patterns and their assigned actions. For each pattern, the source and pattern are put through the `match` function. If there is a pattern that matches the source, the output from the `match` function is put through the action for that pattern. If the output is nowhere in the movie database, the query returns "No answers". If there is no match, the query returns "I don't understand".

2. What movie did you add to the `movies.py` file?  What year was it made? Any specific reason you added that movie?
I added The Super Mario Bros Movie (2023) because it's pretty much popular at this point and Curious George (2006) because it's a movie from my chldhood.

3. What pattern / action did you add to the paList data structure?  Why do you think that is a useful pattern / action?
I added `who are the actors in %` and assigned it the `actors_by_title` function because I didn't want to assume what the user would know what inputs are and aren't ok.

4. What is chatbot would you create that would be like this?  Describe why you would create it and what it would do.
It might take a while for me to think because there are a lot of good chatbots I want to make.

5. What was the most difficult portion of this assignment?
The most difficult portion of this assignment was the `search_pa_list` function because I had no idea what to do in this function. But now that I've gotten a little context, I was able to make the function.

6. Did you write a new assert for your pattern action?
I didn't write a new assert, but I fixed assert 4.


