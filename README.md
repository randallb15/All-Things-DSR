# Table of Contents 
 
[Weekly Tasks](#Weekly-Tasks)

[All Class Days](#All-Class-Days) 

[Lecture Days](#Lecture-Days)  
 
[Assessment Days](#Assessment-Days) 

[Case Study Days](#Case-Study-Days)  

[Capstone Days](#Capstone-Days) 

[Retro Days](#Retro-Days)

[Career Services Days](#Career-Services-Days)   

[Help Desk](#Help-Desk)  

[Common Fixes](#Common-Fixes)   

[Tuesday Team Meeting](#Tuesday-Team-Meeting)

[Ultipro Stuff](#Ultipro-Stuff)

[How To Videos](#How-To-Videos) 
- [Creating Pairs/Groups Video](https://drive.google.com/file/d/1_2FXEfwQswyXi7L2QyT6RjbIrMmwbIkf/view?usp=sharing)

- [Open Learn modules for upcoming week]()

- [Grade assessments]()

- [Post zoom recording]()

- [Add Assignment Solutions]()

- [Add Assessment Solutions ]()

- [Help desk Video]()

- [Edit Learn Video]()

- (*) [Downloads & API to allow access to Learn]()

- [Ultipro Time Sheet Changes ]()


______________
 
# Weekly Tasks 

## Create pairs for any paired assignment 
Simple code for random list of RPP2 students, which can be used to choose pairs, groups of size k < n, and order of presentations: 
```python
import numpy as np
RPP2_students = ['Becky_MDT', 'Bahar_PST', 'Andrew_EST', 'Mekdi_PST', 'Tony_PST', 'Robert_CT',
                 'Sean_PST', 'Nick_PST', 'Reza_CT', 'Bobby_AZ', 'Di_PST', 'Gary_EST', 
                 'Matthew_EST', 'Shaheer_AZ', 'Marwah_PST']

np.random.choice(RPP2_students, replace=False, size=len(RPP2_students))
```
  **challenges**  
    - Sometimes students may express that they don't want to work with another student. Different instructors handle this differently, posting the proposed pairs/groups to the team allows feedback and maybe adjustments.  
    - Different time zones and work/family schedules can make pair programming difficult for part-time cohorts. 
    
    Ask instructor regarding:   

      - pairing based on time zones or schedules (alternatives to random pairings) 

      - due date extensions with prior approval

## Post Pairs

[pairs how to video](https://drive.google.com/file/d/1_2FXEfwQswyXi7L2QyT6RjbIrMmwbIkf/view?usp=sharing)

[RPP2 Pairs Learn](https://learn-2.galvanize.com/cohorts/2432/blocks/824/content_files/01-subject/07-pairs.md)

[RPP2 Pairs Google Sheeet](https://docs.google.com/spreadsheets/d/1VcBQ9OE8YPqudsBuj6NNbmeWkR7uR8n_VgK8BTgd6TQ/edit#gid=0)

After creating pairs and getting feedback on adjustments, updating this google sheet will make the pairs visible to the students.

## Check Student Facing Calendars

[RPP2 Main Calendar & Weekly Schedule Learn](https://learn-2.galvanize.com/cohorts/2432/blocks/824/content_files/01-subject/06-calendar.md)

[RPP2 Main Calendar Google Sheet](https://calendar.google.com/calendar/u/0/r/week/2021/5/30)
- Check DSR Coverage
- Check lecture, retro, assessment, case-study, capstones, break dates

[RPP2 Weekly Schedule Google Sheet](https://docs.google.com/spreadsheets/d/1zKjOJaTR9sQPTJTx0CW0xDahaO7IezT92HvThWh82Gk/edit#gid=725018318)
 - Are dates and order of modules correct? (Alert PL to discrepancies)
 - Check for Async assignment to be included in announcements

[RPP2 Due Dates Learn](https://learn-2.galvanize.com/cohorts/2432/blocks/824/content_files/01-subject/08-assignment-due-date.md)

[RPP2 Due Dates Google Sheet](https://docs.google.com/spreadsheets/d/1HxucDS629qxuQ1Jy0567M1yIHwIcAyquH5xWe5xL74c/edit#gid=0)

- In general, the due date is a week from the corresponding lecture.  
- Async assignments are due a week from that week's Saturday lecture.
- Paired assignments should be italicized

## Open the Learn modules for upcoming week  
From [RPP2 Learn](https://learn-2.galvanize.com/cohorts/2432/content)
1. **SET UP** tab
2. **Content** tab
3. **<block_name>** block
4. click grey eyeball to right of <block_name>  

Note: In an open block, the eyeball will disappear, but hovering over the <block_name> will reveal a green eyeball that can be clicked on to close the block.

## Fix Learn Typos/Errors/Broken-links   
[RPP2 Learn](https://learn-2.galvanize.com/cohorts/2432)  

[GitHub gSchool](https://github.com/gSchool)

### JUST ONE TIME, get access to gSchool Learn

### For each Learn block, clone learn gSchool module into your Learn directory
> if you have already cloned the repo,
> - You don't need to re-clone the repo, just navigate in to repo
> - REMEMBER TO PULL after navigating into repo

```bash
cd Desktop/Galvanize/LEARN
git clone https://github.com/gSchool/dsi-learn-clustering-methods.git # if not yet cloned
cd dsi-learn-clustering-methods
git pull 
git checkout RPP2 
git pull
code .
```
Make necessary changes in VSCode markdown file(s)

Save changes

```bash
learn preview -o .
git add .
git commit -m 'description of changes'
git push origin RPP2
```
In Learn:
1. **SET UP** tab
2. **Repos** tab
3. **<block_name>** block will have a green 'updates' oval
4. click sync arrows OR 3 vertical dots to right (choose update branch) of <block_name>  
5. Double check that the changes are working in the student facing Learn block.

[Edit Learn Video](#Edit-Learn-Video)  


## Weekly Slack Announcements
- ### due dates for current assignments
- ### reminder to submit assignments
  - #### bold async assignment(s)
  - #### italicize paired assignment(s)
- ### notice of upcoming assessments
- ### notice of upcoming case-study or capstone days  
> ### check with PL and instructors for other announcements

______________

# All Class Days  
## Attendance
Link to HUB doc Attendance tab:
[RPP2 Attendance](https://docs.google.com/spreadsheets/d/1zKjOJaTR9sQPTJTx0CW0xDahaO7IezT92HvThWh82Gk/edit#gid=373849433)  

> RPP2 has a different attendance policy than future cohorts. Confirm policy with PL.

  - Within the Attendance tab the process is very self-explanatory.  
  - Holding up fingers to show the instructor how many students we are waiting on has been effective in RPP2.


## Create & recreate Zoom breakout rooms as needed  
- Automatically assign rooms
- Manually assign rooms
- Allow participants to choose rooms

## Assignment Submissions

### [RPP2 Checking Submissions in Learn](https://learn-2.galvanize.com/cohorts/2432/unit_progress)  
1. **UNIT PROGRESS** tab
2. **<block_name>** use down arrow
3. <Assignment_name> use down arrow   
4. <Assignment_Submission> small circle indicates 'submitted'

### [RPP2 Update Assignment Submission Doc](https://docs.google.com/spreadsheets/d/1zKjOJaTR9sQPTJTx0CW0xDahaO7IezT92HvThWh82Gk/edit#gid=1371301276)  

A one-class grace period was effective in RPP2. For example, if the assignment is due on Tuesday, checking for that assignment submission + updating the google sheet on Thursday worked well.

# Lecture Days   

## Sign into Zoom with cohort email
- Permission to open the classroom
- Permission to record
- Permission to make breakout rooms 
- Permission to join breakout rooms
- Permission to assign and move students to breakout rooms
- Change your Zoom name to '<your_name> DSR'

## Record Lecture
> Every cohort needs a Tony :)  All the sticky notes & alarms in the world aren't as effective as multiple people checking that the lectures is being recorded. Let the cohort know you appreciate their help.

## [RPP2 Provide Access to Assignment Repo](https://github.com/GalvanizeDataScience/convolutional-neural-nets)   
*github CNN for example*  

> Open at the beginning of class, not prior to lecture

1. Settings
2. Manage Access
3. Enter and Confirm your password
4. Invite teams or people (READ Access)
5. For RPP2, add **GalvanizeDataScience/21-02-ds-rpp**
6. For RPP2, Confirm: Add GalvanizeDataScience/21-02-ds-rpp

## [RPP2 Add Solutions to Cohort's Solutions Repo]()  
> RPP2 opens solutions with assignment.   

> This will not be the case for RPP3. RPP3 solutions will be posted on the due date.

[RPP2 solutions repo](https://github.com/GalvanizeDataScience/solutions-rpp2.git)

ONLY DO THIS PART THE FIRST TIME:

1. git clone <cohort_solution_repo>
2. cd into solutions repo
3. git remote add solutions <cohort_solution_repo>
4. git fetch solutions main

DO THIS EVERY TIME:

1. cd into solutions repo
2. git pull
3. git fetch solutions main
4. git checkout solutions/main oop
> using oop as an example
5. git add .
6. git commit -m 'add oop solutions'
7. git push


## Daily Announcements  

Check-in with Instructor & PL prior to class regarding announcements 

## Post [lecture recording](https://zoom.us/) after it processes 
- edit recording name to include: *instructor, topic(s), date*
- check that no passcode is required


In a terminal, from the learn repo <dsi-learn-block>
```bash
git pull
git checkout RPP2
git pull (do we need to re-pull from each branch?)
code .
```
In VSCode: add lecture recording link.
Back in terminal:
```bash
learn preview -o . #the -o opens a preview Learn block to see changes
git add .
git commit -m 'add lecture recording'
git push origin RPP2
```

In Learn:
1. **SET UP** tab
2. **Repos** tab
3. **<block_name>** block will have a green 'updates' oval
4. click sync arrows OR 3 vertical dots to right (choose update branch) of <block_name>  
5. Double check that the changes are working in the student facing Learn block.


# Assessment Days 
## Opening
1. Learn.SET UP
2. **Content** tab
3. **Assessments** block
4. **DSI Assessment #** click first eyeball
5. click dropdown arrow to left of **DSI Assessment #**
6. click second eyeball

## Timing Assessment 
- 60 minute strict time limit
- Count down announcements at: 30, 15, 5 minutes left

## Checking Submission of Assessment 
1. [RPP2 Learn](https://learn-2.galvanize.com/cohorts/2432)
2. **DSI Assesment_#** block 
3. **Results** table   
4. **Status** column

## Adding Assessment Solutions to the Solutions repo

```bash
cd Desktop/Galvanize/RPP2/solutions-rpp2 # navigate into solutions repo 
git pull
git fetch solutions main
git checkout solutions/main assessments/assessments-0 # using 0 as an example
git add .
git commit -m 'add assessment-0 solutions'
git push
```

## Adding Assessment Solutions to Learn
[RPP2 Learn Assessment Solution Block](https://learn-2.galvanize.com/cohorts/2432/blocks/1045/content_files/01-assessment-solutions/01-solutions.md) 

## Grading Assessments
- ### In Learn  
[RPP2 Learn Assessment 0](https://learn-2.galvanize.com/cohorts/2432/blocks/115/content_files/assessment-0.md?assessment=true)

- ### In Hub (2 places to input grades)
[RPP2 Assessment point Google doc](https://docs.google.com/spreadsheets/d/1zKjOJaTR9sQPTJTx0CW0xDahaO7IezT92HvThWh82Gk/edit#gid=231386871)  

[RPP2 Assessment results Google doc](https://docs.google.com/spreadsheets/d/1zKjOJaTR9sQPTJTx0CW0xDahaO7IezT92HvThWh82Gk/edit#gid=341773588)

Assessment statistics will populate after inputs are complete, which can be used to add statistics to Learn:

- ### Adding Assessment Statistics to Learn
[RPP2 Learn Assessment Solution Block](https://learn-2.galvanize.com/cohorts/2432/blocks/1045/content_files/01-assessment-solutions/01-solutions.md)



# Case Study Days  
## Generate Groups of 3/4 students  
Simple code for random list of RPP2 students, which can be used to choose pairs, groups of size k < n, and order of presentations: 
```python
import numpy as np
RPP2_students = ['Becky_MDT', 'Bahar_PST', 'Andrew_EST', 'Mekdi_PST', 'Tony_PST', 'Robert_CT',
                 'Sean_PST?', 'Nick_PST', 'Reza_CT', 'Bobby_AZ', 'Di_PST', 'Gary_EST', 
                 'Matthew_EST', 'Shaheer_AZ', 'Marwah_PST']

np.random.choice(RPP2_students, replace=False, size=len(RPP2_students))
```

## Assign breakout rooms 

## Progress checks

1. MVP plan

- use MVP+, MVP++, future work to handle overly optimistic plans

- plan should include hypothetic audience

2. Github repo  
>forked by student A  
>cloned from student A by other team members 

- [Ryan & Heather example video](https://zoom.us/rec/share/WYhK0DE1ZBs4lvN33JDCp3eMHl7QTycVjlaRXbWCgaXcVvwJ8CBzsrVFqjvMln1T.oETxz6XDF0QB1LuA?startTime=1616691949000)
    
- suggest VSCode Live Share for README.md  

3. Slide deck/presentation tool started  

## Presentations

# Capstone Days    

## Manually Assign breakout rooms 

## Stand-ups
[RPP2 Stand-ups Sheet](https://docs.google.com/spreadsheets/d/1lztQRmiV1DQrzRyrgY0Lc_VqVFRYh7hXf0kuqDLs66k/edit#gid=0) 
Check:
1. Well defined MVP
2. Cohesive, narrow Story
3. GitHub repo + README + Slide Deck started
Elevator Pitch (30 second engaging overview) 
Follow-up on meeting goals from last stand-up
Goals for today
ABC always be committing
  
## Presentations
[RPP2 Presentation Sheet](https://docs.google.com/spreadsheets/d/1lztQRmiV1DQrzRyrgY0Lc_VqVFRYh7hXf0kuqDLs66k/edit#gid=0)


# Retro Days  

## [RPP2 Retro](https://drive.google.com/drive/u/2/folders/1LC2jRkS-K0JrgN7rCHQiBcwpk-GR7YU1) support as directed by PL

## Kudos from DSRs after student's are done

# Career Services Days  

## Record with permission from CSM

## Appropriate time for DSRs to turn off camera and complete other [tasks](#Weekly-Tasks)

## Post CSM presentation

Temporarily CSM resources will be stored in 
[Important Information > Career Services Videos](https://learn-2.galvanize.com/cohorts/2432/blocks/824/content_files/01-subject/10-career-service-videos.md) 

CSM Learn block is being created.

## Post [CSM recording](https://zoom.us/) after it processes 
- edit recording name to include: *instructor, topic(s), date*
- check that no passcode is required
   
```bash
cd dsi-learn-welcome-template
git pull  
git checkout RPP2 
git pull  
code .
```
Add zoom link in career services videos markdown file in VSCode

Save changes

```bash
learn preview -o .
git add .
git commit -m 'added CSM video'
git push origin RPP2
```
In Learn:
1. **SET UP** tab
2. **Repos** tab
3. **<block_name>** block will have a green 'updates' oval
4. click sync arrows OR 3 vertical dots to right (choose update branch) of <block_name>  
5. Double check that the changes are working in the student facing Learn block.

_______________

# Help Desk  
Encourage students to use the assignments channel to troubleshoot problems. Teach students to fish. The goal is helping the student find the answer, not providing the answer.

# Common-Fixes

## Docker  

Ubuntu users may need to use sudo before docker commands
https://stackoverflow.com/questions/48957195/how-to-fix-docker-got-permission-denied-issue


If you do a git command with an open docker container, you may have to stop the container in order for the updates to show up.
https://github.com/moby/moby/issues/15793#issuecomment-135411504


- ### sparkbook

$ docker run --name sparkbook -p 8881:8888 -v "$PWD":/home/jovyan/work jupyter/pyspark-notebook start.sh jupyter lab --LabApp.token=''

- ### pgserv  

$ docker run --name pgserv -d -p 5432:5432 -v "$PWD":/home/data -e POSTGRES_PASSWORD='galvanize' skylarenglish/galvanize:galv_db
^only do this once. If there is a problem:
	docker rm pgserv or docker container rm pgserv  and run again.
docker start pgserv
docker exec -it pgserv bash
cd home/data/*from root of container 
To leave the container:
exit
Docker stop pgserv
____

psycopg2 Install probs, try:
conda update --all
conda install psycopg2 
____

Working with psycopg2 in notebook/script?
import psycopg2 as pg2
conn = pg2.connect(dbname='readychef',
                     host='localhost',
                     user='postgres',
                     password='galvanize')
cur = conn.cursor()
query = '''select * from events limit 10;'''
cur.execute(query)
for row in cur:
    print(row)


### mongoserver  

If you get into the root directory and can’t navigate to home/data/…
(probably means the docker container ‘mongoserver’ wasn’t initially run with the right path)
From docker mongoserver root:
```bash
exit
docker stop mongoserver
docker rm mongoserver
$ docker run --name mongoserver -p 27017:27017 -v "$PWD":/home/data -d mongo
```

### tensorflow
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
## Github  

[Git Reference Doc](https://github.com/GalvanizeDataScience/course-outline/blob/21-02-DS-RPP/quick-reference/Git.pdf)


### [Kacie's Git Review](https://zoom.us/rec/share/woTbzJ12anB-q_dDd6_g5K_6k6ydmgxMzWVGLncsBQ7hnV_nVNwdfHxNnJuZbS2w.7pkatu8jYvAJ5477?startTime=1619659988000)

### Lecture Pulling
To clone just lectures from the RPT branch
```bash
git clone -b RPT --single-branch https://github.com/GalvanizeDataScience/lectures.git
```

Tired of having to add your credentials to the terminal each time you want to clone or push?
```bash
git config --global credential.helper store
git config --global credential.helper cache
```
OR

```bash
git config --global credential.helper 'cache --timeout=3600'
```

## Unix




## VSCode Environment
____
For the unix assignment, when I try to put the 2015_goog_sorted.csv file into the plot_stock_prices.py code, VSCode and Pylint gives an import error for matplotlib. How do I fix this?
answer:
I figured out how to get this to work. I needed to set up the anaconda environment by typing conda activate env into my python console. The environment can be found by typing 
conda info --envs into the console.
____


## Mac
- “I've run into this problem whenever I update my macbook. “
> xcrun: error: invalid active developer path (/Library/Developer/CommandLineTools), missing xcrun at: /Library/Developer/CommandLineTools/usr/bin/xcrun  

SOLN:
```bash
xcode-select --install
```

## Linux/Unix

## Windows (even though the program may not 'technically' support windows)

Okay I think the substitution for $PWD is %cd%. At least that’s what this article is telling me. https://stackoverflow.com/questions/35767929/using-docker-via-windows-console-includes-invalid-characters-pwd-for-a-local-v

_________________

## Tuesday Team Meetings 
[Asana](https://app.asana.com/0/home/1199688949945059)

## Ultipro Stuff
1. Open incognito window (command+shift+n)
2. Open outlook (make sure you are signed in with k12 email)
3. Open ultipro.com
4. Choose Workforce Management tab
5. Use My Clock to clock in and out

* Time Sheet Change Requests

## Onboarding Stuff
Background check  
I9  
