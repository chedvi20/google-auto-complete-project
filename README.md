# auto complete

This is a program that offers the searcher in a file tree,
the k "best" suggestions (predetermined score) to complete the search key according to the data in the files,

## Description
For each such proposal we will provide the following data: 
* The source of the "path" of the original sentence,
* The sentence itself
* The location of the key in relation to the sentence,
* The score determined in relation to its level of suitability.

The program supports the correction of one typo: Add, replace and skip a character - for which a reduced score will be given

## Getting Started

### Installing

* "pip install dataclasses"

### Preparation stage

* run "init_search_data.py" (  )
* To run on your files update the line
```
path = 'your_path'
```

### Executing program

* run "online.py" ()
* Once the user types in characters and presses Enter the system displays the best K completions
* After viewing the completions the system allows the user to continue typing from where he stopped
* If the user types "#" it means that the user has finished typing for this sentence and can enter a new search

