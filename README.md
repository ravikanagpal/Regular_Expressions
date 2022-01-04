# Intro to NLP - Assignment 1

## Team
|Student name      | CCID       |
|------------------|------------|
|Ravika Nagpal     |  ravika    |
|Seeratpal Jaura   |  seeratpa  |

---

# 2. A list of all the resources used


-   https://regex101.com/ - To test regex

-   https://www.dataquest.io/blog/regex-cheatsheet/ - For revising and using the symbols to generate regex

-   https://python101.pythonlibrary.org/chapter3_lists_dicts.html - For seeing the usuage of dictionaries and tuples

-   https://stackoverflow.com/questions/4664850/how-to-find-all-occurrences-of-a-substring/4664889#4664889 - For seeing how to obtain all occurance of a string


# 3. Execution Instructions

## Setup

```sh
# Setup python virtual environment
$ virtualenv venv --python=python3
$ source venv/bin/activate

# change directory to the repo where we have requirements file
$ cd f2021-asn1-JauraSeerat/

# Install python dependencies
$ pip3 install  -r requirements.txt 
```

## Run

Use the following command in the current directory.

`python3 src/main.py data/dev/ output/dev.csv`

## Data

The assignment's development data can be found inside [data/dev](data/dev).

---

# 4. Design Discussions

-   We discussed and divided the tasks to start with smaller problems and later on addressed the complex portions.
-   We first identified the date patterns from the output files for which we have to write the regex.
-   We divided the patterns amongst us and wrote regex for those patterns using regex101 editor.
-   We used google colab notebook to do the practice work of running those regex for a small set of files and then discussed the regex which were failing for some of the patterns.
-   We have used the dictionary to map the pattern with the expression type in order to identify the pattern associated with the particular match.
-   To look for the bigger patterns, we have used the precedence of offsets in the dataframe and ruled out the row with the lower precedence.
-   We verified our coverage by running a  difference between our output and the sample data provided ('output_dev.csv').





