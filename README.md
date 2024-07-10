# Report for Assignment 1 resit

## Project chosen

Name: pythonping

URL: https://github.com/alessandromaggio/pythonping.git

Number of lines of code and the tool used to count it: The number of lines of code (nloc) is 1023, and the tool used to count the nloc was Lizard. 

Programming language: Python

## Coverage measurement with existing tool

<Inform the name of the existing tool that was executed and how it was executed>
The tool used to measure the coverage was Coverage.py and it was executed by running the command 'sumo coverage run -m unittest discover test' in the terminal.

<Show the coverage results provided by the existing tool with a screenshot>
<img width="1045" alt="Coverage before" src="https://github.com/OrestisKal/pythonping-OK/assets/78654750/a9300377-c5c2-42ef-a75c-f036311b9583">


## Coverage improvement

### Individual tests

<The following is supposed to be repeated for each function (2 in total)>

#### Function 1

Link to commit showing newly added test case to improve coverage:
https://github.com/OrestisKal/pythonping-OK/commit/b5192759d4847b0fdbaf91853f532d52dd3f903f

##### Function 1 coverage, before coverage improvement
<img width="1376" alt="Function1 cov before" src="https://github.com/OrestisKal/pythonping-OK/assets/78654750/c3444eab-78a0-44d1-ba45-df077cb42f0e">


##### Function 1 coverage, after coverage improvement
<img width="1371" alt="Function1 cov 100%" src="https://github.com/OrestisKal/pythonping-OK/assets/78654750/9165ecde-6a07-48a7-8014-f7b5fcfec7ee">


<State the coverage improvement with a number and elaborate on why the coverage is improved>
The coverage improvement is an increase of 100%. Initially, none of the branches were executed, but after creating a new test case that targeted the three branches, including the invisible 'else' branch, each branch was executed. Thus, a 100% branch coverage.

#### Function 2

Link to commit showing additions to existing test case to improve coverage:
https://github.com/OrestisKal/pythonping-OK/commit/5d51b73c06640458bb4d4b9a5cf18858d70bf81c

##### Function 2 coverage, before coverage improvement
<img width="1373" alt="Function2 cov before" src="https://github.com/OrestisKal/pythonping-OK/assets/78654750/07c31d2d-584f-4d27-8fb9-152901d0c0c6">

##### Function 2 coverage, after coverage improvement
<img width="1366" alt="Function2 cov 100%" src="https://github.com/OrestisKal/pythonping-OK/assets/78654750/ab217ecc-a946-4b61-b147-c1cfa414d246">

The coverage improvement is an increase of 100%. To begin with, the branch coverage of the function was 0%, despite having an existing test case. After enhancing the existing test case to call on the function, both branches including the invisible 'else' branch were executed. Thus, a 100%v branch coverage for the function.



### Overall

#### Overall coverage before
<img width="1045" alt="Coverage before" src="https://github.com/OrestisKal/pythonping-OK/assets/78654750/957e29fc-9a0b-4644-a37f-3d01003e1887">


#### Overall coverage after
<img width="945" alt="Coverage after" src="https://github.com/OrestisKal/pythonping-OK/assets/78654750/ea1ab1e9-0bcf-41d8-8f7a-1ece4fd9af6a">

