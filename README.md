# data_1_checks
Code Louisville Data 1 Knowledge Checks

Knowledge Check 1

To complete the first knowledge check, do the following:Create a GitHub repo called "data_1_checks". You will upload ALL knowledge checks to this repo in the future.
Send that link to your mentor so they can check it when you finish the assignment.Make a .py (or .ipynb) file that contains the following (your choice of editor does not matter!):

a statement that prints "hello world!"
a list populated with several values. They can be strings / integers / floats etc. Then, print() one of those values either to the prompt or in a cell (if using Jupyter Notebook)
a dictionary populated with two keys and two values. Print one of the values just like you did above.
a tuple with 4 values. Print one of them.

Commit your changes.Push your changes to your repo and notify your mentor!

# Welcome to Knowledge Check 2! 

I hope the videos are going well. Today, we're going to try loading some data and generating a plot using pandas and seaborn. Here are your instructions: 

1. Create a new file in your "data_1_checks" repository titled "kc_2". Remember, you can use .py files or .ipynb. The only problem with colab (what this was written in) is that it's a little trickier to commit to GitHub with it (at least as of this writing in April 2022). We really want you to be able to work with git and GitHub seamlessly, so you have to go the slightly longer route now of doing everything locally rather than on this server.
2. Make a folder titled "assets" in your repo. This is where you will put any CSVs or other files you download you want to load in. This is a nice way to organize data - if you drop everything in your main folder (in your case, "data_1_checks") you'll have a bunch of random data floating around intermingled with the files.
3. Load your data into a DataFrame. 
4. Plot ANY of your data with seaborn (or matplotlib, or any other plotting tool if you have one you really like).
5. Push your changes to GitHub, and make sure to turn in the GitHub link into Google Classroom.

---


This will test your ability to find data and load it in. It sounds simple, but working with file paths to get your data into Python can be a little tricky at first. As a hint, Python will always search the current directory you're in. In Jupyter Notebook, you can access the command line with the exclamation point like this: 
```
!dir
```
Once you're in your project directory, if you have them named like I do above, your data will be located at: 
```
assets/data.csv
```
Note the exact path will depend on your operating system. This is assuming a file named "data.csv", yours will probably be named differently.
