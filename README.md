# BUSA8090_Assignment_1_Task_1
Busa8090 Assignment 1 Task 1
#Question 1
#!/bin/bash
ls -lt | tail –1

#Question 2
#!/bin/bash
if [[ $* == “” ]] ; then
        echo “'This is NOT funny'”
else
        echo “'This is funny'”
fi
