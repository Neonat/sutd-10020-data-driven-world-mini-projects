# Data Driven World mini-project starters | SUTD 10.020

These are the pair-programming starters for SUTD 10.020 Data Driven World. The first project puts a sorting algorithm in a web page. The next introduces shared maths challenges and a database. The optional third handout explores a computer opponent for Tic Tac Toe. Each folder contains starter code and exercises to complete privately.

The course [sorting handout](mp_sort/Readme.md) explains the choice of Transcrypt. Students write the browser logic in the Python they study in class, and Transcrypt compiles it to JavaScript. Flask serves the pages and handles requests on the server. In the maths project, SQLAlchemy models represent the data that must persist between requests.

| Project | Where to start |
| --- | --- |
| [Sorting](mp_sort/Readme.md) | Follow the handout alongside the [browser-side Python](mp_sort/app/static/library.py) to see how the sorting exercise connects to the page. |
| [Maths quiz](mp_calc/Readme.md) | Use the [forms guide](mp_calc/Forms.md) and [database notes](mp_calc/Database.md) with the exercises on creating and taking challenges. |
| [Optional Tic Tac Toe](mp_tictactoe/Readme.md) | The handout covers game logic, a computer opponent, and game records. The [models](mp_tictactoe/app/models.py) include users and saved state. |
| [Reusable Flask template](mp_template/) | A starter based on the maths quiz that you can adapt for a separate project. |

## Use the course materials

Each project has its own `Pipfile` and handout. Start in the selected folder and use the checkout's actual name when the handout uses `d2w_mini_projects`. The handouts describe historical teaching environments. For example, the Tic Tac Toe handout also refers to a `requirements.txt` file that the folder does not contain.

This fork preserves starter material from [Data-Driven-World/d2w_mini_projects](https://github.com/Data-Driven-World/d2w_mini_projects). Copyright © 2019 Oka Kurniawan. [MIT licence](LICENSE)

## Original assignment guidance

Mini Project templates for Data Driven World. Click "Use This Template" button on the top right and create a **private repository**. You are not allowed to create a public repository and post your solution online.

## Mini Project 1
This mini project is to create a simple html pages to generate random number and sort them.

[Handout](mp_sort/Readme.md)

## Mini Project 2
This mini project is to create a simple web application for math quiz where users can create simple math challenges and take up challenge from others.

[Handout](mp_calc/Readme.md)

## (Optional ) Mini Project 3

This mini project is to create a simple AI Tic Tac Toe game where a user can play Tic Tac Toe against a computer. There is no grading on this part and you just need to explore on your own.

[Handout](mp_tictactoe/Readme.md)

## Groupings

Students should work as a pair and practice pair programming in doing the mini project.
