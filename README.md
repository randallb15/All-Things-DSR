# List of Resonsibilities   
[All Class Days](#All-Class-Days)  

[Weekly Tasks](#Weekly-Tasks)

[Lecture Days](#Lecture-Days)  
 
[Assessment Days](#Assessment-Days)  

[Career Services Days](#Career-Services-Days)  

[Case Study Days](#Case-Study-Days)  

[Capstone-Days](#Capstone-Days)  

[Help-Desk](#Help-Desk)  

[How To Videos](#How-To-Videos)  

[Common Fixes](#Common-Fixes)   


# List-of-Resonsibilities  

# All Class Days  
- ## Attendance  

    - ### [RPP2 Attendance](https://docs.google.com/spreadsheets/d/1zKjOJaTR9sQPTJTx0CW0xDahaO7IezT92HvThWh82Gk/edit#gid=373849433)   

- ## Create & recreate Zoom breakout rooms as needed   

- ## [Update Assignment Submission Doc](https://docs.google.com/spreadsheets/d/1zKjOJaTR9sQPTJTx0CW0xDahaO7IezT92HvThWh82Gk/edit#gid=1371301276)

# Lecture Days   

- ## Record Lecture
> Every cohort needs a Tony :)  All the sticky notes & alarms in the world aren't as effective as multiple people checking that the lectures is being recorded. Let the cohort know you appreciate their help.

- ## Post [lecture recording](https://zoom.us/) after it processes  
 - check that no passcode is required

# Weekly Tasks
- ## Create pairs for any paired assignment  

- ## Open next Learn modules for upcoming week  

  - ### check that links are working  

  - ### check that [Pairs RPP2](https://docs.google.com/spreadsheets/d/1VcBQ9OE8YPqudsBuj6NNbmeWkR7uR8n_VgK8BTgd6TQ/edit#gid=0) are posted for any pairs assignment  

- ## Add upcoming due dates to [RPP2 Google doc](https://docs.google.com/spreadsheets/d/1HxucDS629qxuQ1Jy0567M1yIHwIcAyquH5xWe5xL74c/edit#gid=0)

- ## Slack Announcements
  - ### due dates for current assignments
  - ### reminder to submit assignments
  - ### notice of upcoming assessments
  - ### highlight async assignment(s)
  - ### highlight paired assignment(s)
  - ### notice of upcoming case-study or capstone days  
  > ### check with PL and instructors for other announcements

# Retro Days  
- ## [RPP2 Retro](https://drive.google.com/drive/u/2/folders/1LC2jRkS-K0JrgN7rCHQiBcwpk-GR7YU1) support as directed by PL
- ## Kudos if you have some

# Assessment Days 
- ## Opening
1. Learn.SET UP
2. **Content** tab
3. **Assessments** block
4. **DSI Assessment #** click first eyeball
5. click dropdown arrow to left of **DSI Assessment #**
6. click second eyeball

- ## Timing Assessment 
    - 60 minute strict time limit
    - Count down announcements at: 30, 15, 5 minutes left

- ## Checking Submission of Assessment 
1. [RPP2 Learn](https://learn-2.galvanize.com/cohorts/2432)
2. **DSI Assesment_#** block 
3. **Results** table   
4. **Status** column

- ## Posting Solutions to Assessments

- ## Grading Assessments

   - ### In Learn  

     - #### [RPP2 Learn]()

   - ### In Hub

     - #### [RPP2 HUB](https://docs.google.com/spreadsheets/d/1zKjOJaTR9sQPTJTx0CW0xDahaO7IezT92HvThWh82Gk/edit#gid=231386871)  

# Career Services Days  

- ## Record with permission from CSM

- ## Appropriate time for DSRs to turn off camera and complete other [tasks](#List of Responsibilities)

- ## Post lecture under [Important Information.Extra Resources](https://learn-2.galvanize.com/cohorts/2432/blocks/824/content_files/01-subject/09-class-resources.md)
   
   - [Posting Zoom Recordings](#Posting-Zoom-Recordings)

# Case Study Days  
- ## Assign breakout rooms 
- ## Progress checks
- ## Presentations

# Capstone Days    
- ## Assign breakout rooms  
- ## [Stand-ups](https://docs.google.com/spreadsheets/d/1lztQRmiV1DQrzRyrgY0Lc_VqVFRYh7hXf0kuqDLs66k/edit#gid=0) 
- ## Presentations

# Help Desk  

# How To Videos
- ## Open Learn modules for upcoming week
- ## Grade assessments
- ## Post zoom recording
- ## Add solutions for assessments/solutions
- ## Help desk

# Common-Fixes
- ## Docker
  - ### sparkbook
  - ### pgserv
  - ### mongoserver
  - ### tensorflow
    ```bash 
    docker run -it --name tensorflow -p 8888:8888 -v "$PWD":/tf tensorflow/tensorflow:2.0.0a0-py3-jupyter
 
    docker start tensorflow
    docker exec -it tensorflow bash
    ```
    Navigate to repo if you want 
    cd <path>
    In browser type: localhost:8888/
    To get token (if you don’t have a password set up)
    jupyter notebook list
    Something like this will allow you to copy and paste the highlighted part: token=f47d7c92d31140b3e12c0a68703c0a7e64944133a9e149e9
    Hopefully now, just navigate to the the repo/project
    To exit the container (all work show be saved on your local version too)
    exit
    ```bash
    docker stop tensorflow
    docker ps (to make sure)
    ```
- ## Github
    - ## Lecture Pulling
- ## VSCode Environment
- ## Mac
  - “I've run into this problem whenever I update my macbook. “
> xcrun: error: invalid active developer path (/Library/Developer/CommandLineTools), missing xcrun at: /Library/Developer/CommandLineTools/usr/bin/xcrun  

SOLN:
```bash
xcode-select --install
```

- ## Linux/Unix
- ## Windows (even though we say we don't support windows)
- ## 