# Assignment 3 - Write UP

## Description
This assignment completes our movie chatbot system by implementing action functions that query our movie database and building a natural language interface. You implemented functions to search for movies by year, director, and actors, as well as the core search system that matches user queries to appropriate database operations. This builds directly on the pattern matching work from Assignment 2 to create a functional conversational AI system.

## What to complete
1. Complete all action functions in `a3.py` (title_by_year, title_by_year_range, etc.)
2. Implement the `search_pa_list` function to handle pattern matching and responses  
3. Add at least one new movie to the database with proper formatting
4. Create a new pattern/action pair and add it to the pa_list
5. Ensure all provided assert statements pass
6. Complete the reflection questions below
7. Push your code to github for grading

## Reflection Questions

1. What are some key programming concepts or techniques that you learned while completing this assignment?
I learned how to finalize some statements in Python in the way I usually would in Java. Also, I got to make different files (I forgot what they were called, like the different sections of a project. For example, some of these are a3.py, match.py, movies.py) interact with each other. 


2. How does the overall movie chatbot system work? Explain the flow from when a user types a query to when they receive an answer.
It pulls the user input to show the user what they want to see from the database's limited saved data. It does it by giving back movie directors, actors, years made, movies by a specific director, etc., using the methods stated in a3.py.


3. What are some real-world applications where this type of pattern-matching chatbot system could be useful? How might you extend or improve this system for practical use?
Google probably uses a simpler method such like this one to give users the results they are looking for. However, I can probably improve this system if I can find a way to get user input to build a sentence that would give the user what they want. An algoritm in which the code usually doesn't print "data not available" for better user accessibility and conformity. 