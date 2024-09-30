# sutis-task
An example of SUTIS task folder format

exampletask folder - this folder contains all the files required for acknowledgement of the task. Name of the folder is not tied to task. The folder contains the following files:

## task.json

This file contains the task details. The file contains the following fields: 
- name: name of the task
- short_description: description that will be shown in sidebar
- points: points for the task   
- creator: creator of the task 

## readme.md
This file is a markdown file that contains the detailed description of the task. This will be rendered in the main content area when the task is selected.

## code.txt
This is the code template for the task. This will be shown in the code editor when the task is selected. (We don't want our students to waste time on writing boilerplate code)

## output.txt
This file contains the expected output of the code. This will be used to validate the code written by the student.
