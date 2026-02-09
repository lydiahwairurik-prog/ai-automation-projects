##Workout Input & Analysis Automation

**Description**
This workflow sends an email everyday with an inbuilt form that the user is to fill. The form asks what day it is, part of the body worked on and number of sets and reps done
This information is then sent to the workout databasefor storage
The workflow the waiys for 5 days where the data in the databse is then sent to an LLM which analyses the workouts done
The LLM then recommends what sets to add, workouts to add to the routine and what to exoect after doing the workouts

**Nodes Used**
-Scheduled Trigger
-Send Email and Wait for Response
-Google Sheets
-Wait
-Basic LLM chain
-Send Email
-No Operation, do nothing

**Use Case**
Best for begginers who want to improve accountability but also don't want to do it manually

