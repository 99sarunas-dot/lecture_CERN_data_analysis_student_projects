#Log for everything 

1) you give csv, the scripts spit out a latex table, also calculates uncertainties. 

2) Folder organizer

3) Error calculator 

4) AI model to predict stars

5) csv cleaner

6) mini report

WHAT IM DOING: transforming a messy CSV to a clean one.

FEATURES:

Im doing a project where i automate cleaning a csv. Im planning for the user to choose a csv, what he wants to do with it and then automating to do it and spit out a clean csv. Please write a function that asks the user to list the directory from where to get the file and if there is csv files ask which file does he want to clean(numbered)

Added file selection script.

 """
    Text-based CSV chooser starting from the current working directory.
    - Lists folders and .csv files
    - Type number to go into folder / select file
    - Type 'back' to go up
    - Type 'quit' to exit
    Returns: full path to selected CSV, or None if quit.
    """

SHOULD RUN WITH PYTHON FILE NOT IN TERMINAL

"""
    Allows selecting multiple actions for a CSV file.
    Returns a list of chosen actions, or None if cancelled.
    """

Main.py - choosing file and actions; running actions in the right order; saving the cleaned file
Actions.py - Every action
Config.py - place to define mappings and known units
utils.py --- ???

"""
    Removes:
    - rows where ALL values are empty/NaN
    - columns where ALL values are empty/NaN
    Returns a cleaned DataFrame.
    """

Strip whitepsace --> Normalize missing values --> Remove empty rows and collumns --> Fix deciman commas --> Extract value+unit from cells --> Detect units from collumn names --> 

Im doing csv file cleaner project, it should be something used for physics data csv file cleaning, mostly i would like to use to for my own lab works, that i have on my studies: this is my code so far. I have written to add: .Please also generate a csv file to test this.