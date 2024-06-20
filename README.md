# To-Do List Application

**Ethan Landers | June 2024**

I followed along with [this YouTube tutorial](https://www.youtube.com/watch?v=llbtoQTt4qw) to develop this to-do list application.

[Here](https://github.com/divanov11/Django-To-Do-list-with-user-authentication) is the 
source code created by the YouTube video's instructor for this to-do list application.

## How to run the program locally
1. Install Django on the terminal by running the command `pip install django`.
2. Run the command `python manage.py runserver` in the terminal. 
3. The application server can then be accessed locally at http://127.0.0.1:8000/.

## Application Bugs/Errors
1. The logout functionality showed in the tutorial is apparently not supported anymore in 2024, so it's implementation is not functional. I will determine a solution in the near future.
2. main.html says there is an error here:
```
            h1,
            h2,
            h3,
            h4,
            h5,
            h6,
                {  
                    font-family: 'Raleway', sans-serif;
            }
```