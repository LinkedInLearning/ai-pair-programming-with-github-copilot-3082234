# AI Pair Programming with GitHub Copilot
This is the repository for the LinkedIn Learning course AI Pair Programming with GitHub Copilot. The full course is available from [LinkedIn Learning][lil-course-url].

![AI Pair Programming with GitHub Copilot][lil-thumbnail-url] 

The future of programming is all about collaboration—humans working with machines to achieve exciting and unimagined results. AI pair programming, which integrates human- and machine-generated code, is a prime example of a tool that alleviates tedious, menial tasks to let developers focus their attention on higher-level concerns. In this course, instructor Ronnie Sheer shows you how to get the most out of GitHub Copilot, one of the most useful and impactful new tools for streamlining software development with AI.

Get a comprehensive introduction on how to use Copilot to integrate your coding with the latest AI technology. Ronnie goes over the major features of the application, focusing specifically on Python and JavaScript, and using back-end and front-end Copilot tools. By the end of this course, you’ll be prepared to create data models, implement REST APIs, and write tests, client-side code and templates, HTML, CSS, and more.

## Instructions
This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches
The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:
	
    Add changes to git using this command: git add .
	Commit changes using this command: git commit -m "some message"

## Installing
1. To use these exercise files with a unix terminal:
	- make sure you have [python3 available here](https://www.python.org/)
	- navigate to `cd expense_calculator/`
	- run `git checkout 04_02`
	- run `pwd` and make sure that the path ends with `ai-pair-programming-with-github-copilot-3082234/expense_calculator/`
	- create a python virtual env to isolate dependencies `python3 -m venv venv`
	- activate the virtual env 'source venv/bin/activate'
	- run `python manage.py migrate` to setup the database
	- run `python manage.py runserver`
	- visit <http://localhost:8000/> or <http://localhost:8000/api/expenses/>


### Instructor

Ronnie Sheer 
                            
Software Developer and Instructor

                            

Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/ronnie-sheer).

[lil-course-url]: https://www.linkedin.com/learning/ai-pair-programming-with-github-copilot
[lil-thumbnail-url]: https://cdn.lynda.com/course/3082234/3082234-1661885119709-16x9.jpg




