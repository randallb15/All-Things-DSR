# Table of Contents 

[RPP2 Main Hub](#RPP2-Main-Hub)
 
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

[Tuesday Team Meeting](#Tuesday-Team-Meetings)

[Ultipro Stuff](#Ultipro-Stuff)

How To Videos

- [Updating Pairs How To Video](https://drive.google.com/file/d/1_2FXEfwQswyXi7L2QyT6RjbIrMmwbIkf/view?usp=sharing)

- [Updating Due Dates How To Video](https://drive.google.com/file/d/1_2FXEfwQswyXi7L2QyT6RjbIrMmwbIkf/view?usp=sharing)

- [Open Learn modules for upcoming week](https://drive.google.com/file/d/16Stfq6gfBHQslPfDbP9OzCEp8A8c6BRr/view?usp=sharing)

- [Editing Learn (fix solutions link example)](https://drive.google.com/file/d/1OaBNzZQJIIFwXwZRk0uqwkXwvq2vralc/view?usp=sharing)

- [Editing Learn (hide broken link example](https://drive.google.com/file/d/1aTDXZ041Qyp9aeYL9An-F-TOkYZlpXKa/view?usp=sharing)

- [Checking & Updating Assignment Submissions in Learn](https://drive.google.com/file/d/1BvwxMJU055kYyfC1eC52urwPriOdBGa9/view?usp=sharing)

- [Granting Access to Assignment Repo](https://drive.google.com/file/d/1UgR1OuQ_9dy9LSDXtgmXyxRhnAFqVEhH/view?usp=sharing)

- [Add Assignment Solutions](https://drive.google.com/file/d/1-bMnSAy1uYL60b3aFw4e72U7_M1dByAN/view?usp=sharing)

- [Post zoom lecture recording](https://drive.google.com/file/d/1HHMIrfLhJuhUm20fqOLfy-5EEF-cjxKJ/view?usp=sharing)

- [Opening Assessments in Learn](https://drive.google.com/file/d/1L_zHyMqH56RJAw6YmKtpJfbVEJH8JeJc/view?usp=sharing)

- [FRI 5/28 Grade assessments]()

- [FRI 5/28 Add Assessment Solutions]()

- [Ultipro Clock In/Out + Time Sheet Changes](https://drive.google.com/file/d/1YSCi5f5xv8xA5YE6Mao7llonSldUH8J8/view?usp=sharing)


______________
 
# [RPP2 Main Hub](https://docs.google.com/spreadsheets/d/1zKjOJaTR9sQPTJTx0CW0xDahaO7IezT92HvThWh82Gk/edit#gid=231386871)

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

Note: 
* PL implementing new pairs structure as of 5/25/21. 
* Repo to be updated with details (e.g. designated scheduler).

[RPP2 Pairs Learn](https://learn-2.galvanize.com/cohorts/2432/blocks/824/content_files/01-subject/07-pairs.md)

[RPP2 Pairs Google Sheeet](https://docs.google.com/spreadsheets/d/1VcBQ9OE8YPqudsBuj6NNbmeWkR7uR8n_VgK8BTgd6TQ/edit#gid=0)

After creating pairs and getting feedback on adjustments, updating this google sheet will make the pairs visible to the students.

[* updating pairs how to video](https://drive.google.com/file/d/1_2FXEfwQswyXi7L2QyT6RjbIrMmwbIkf/view?usp=sharing)

## Check Student Facing Calendars + Update Due Dates

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

[* updating due dates how to video](https://drive.google.com/file/d/1_2FXEfwQswyXi7L2QyT6RjbIrMmwbIkf/view?usp=sharing)

## Open the Learn Modules for Upcoming Week  
From [RPP2 Learn](https://learn-2.galvanize.com/cohorts/2432/content)
1. **SET UP** tab
2. **Content** tab
3. **<block_name>** block
4. click grey eyeball to right of <block_name>  

Note: In an open block, the eyeball will disappear, but hovering over the <block_name> will reveal a green eyeball that can be clicked on to close the block.

[* open learn modules for upcoming week how to video](https://drive.google.com/file/d/16Stfq6gfBHQslPfDbP9OzCEp8A8c6BRr/view?usp=sharing)

## Fix Learn Typos/Errors/Broken-links   
[RPP2 Learn](https://learn-2.galvanize.com/cohorts/2432)  

[GitHub gSchool](https://github.com/gSchool)


### JUST ONE TIME, get access to gSchool Learn

Follow the repo or the steps below (I hope)

1. [Install Learn in terminal](https://github.com/gSchool/glearn-cli/blob/master/README.md)

```bash
brew tap gSchool/learn
brew install learn
brew list # look for 'learn'
learn set --api_token=<api token found in “API Token” tab under username in top right corner of Learn>
```
[Learn site API token generator](https://learn-2.galvanize.com/api_token)

> If you see this error:

> Error: The following directories are not writable by your user: /usr/local/bin. You should change the ownership of these directories to your user.
* use the suggestion the terminal gives
```bash
sudo chown -R $(whoami) /usr/local/bin
```
* use brew doctor to find any warnings you might have with brew

**Create a directory to store all the Learn repos: Desktop/Galvanize/RPP2/LEARN**

### For each Learn block, clone learn gSchool module into your Learn directory
> if you have already cloned the repo,
> - You don't need to re-clone the repo, just navigate in to repo
> - REMEMBER TO PULL after navigating into repo

```bash
cd Desktop/Galvanize/LEARN
git clone https://github.com/gSchool/dsi-learn-clustering-methods.git # if not yet cloned
cd dsi-learn-clustering-methods
git pull origin RPP2  # git pull will not update all branches
git checkout RPP2 
code .
```
Make necessary changes in VSCode markdown file(s)

[RPP2 solutions repo link](https://github.com/GalvanizeDataScience/solutions-rpp2)

Save changes

```bash
git status  # will  show the modified files
learn preview -o .  # opens a 'practice' Learn block to see repo after changes
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

[* editing Learn (fix solutions link example)](https://drive.google.com/file/d/1OaBNzZQJIIFwXwZRk0uqwkXwvq2vralc/view?usp=sharing)

[* editing Learn (hide broken link example](https://drive.google.com/file/d/1aTDXZ041Qyp9aeYL9An-F-TOkYZlpXKa/view?usp=sharing)


## Weekly Slack Announcements
- ### due dates for current assignments
- ### reminder to submit assignments
  - #### bold async assignment(s)
  - #### italicize paired assignment(s)
- ### notice of upcoming assessments
- ### notice of upcoming case-study or capstone days  
> ### check with PL and instructors for other announcements

[Announcement Example Image](https://drive.google.com/file/d/1LzQ-3ANuL5Tuwv6pitsJpISPrPRVKRWg/view?usp=sharing)
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

### [RPP2 Checking Assignment Submissions in Learn](https://learn-2.galvanize.com/cohorts/2432/unit_progress)  
1. **UNIT PROGRESS** tab
2. **<block_name>** use down arrow
3. <Assignment_name> use down arrow   
4. <Assignment_Submission> small circle indicates 'submitted'

### [RPP2 Update Assignment Submission Sheet](https://docs.google.com/spreadsheets/d/1zKjOJaTR9sQPTJTx0CW0xDahaO7IezT92HvThWh82Gk/edit#gid=1371301276)  

A one-class grace has bee the norm for RPP2. For example, if the assignment is due on Tuesday, checking for that assignment submission + updating the google sheet on Thursday worked well. At the discretion of the instructor/PL, students may ask for an extension to the due date.

[* checking and updating assignment submissions how to video](https://drive.google.com/file/d/1BvwxMJU055kYyfC1eC52urwPriOdBGa9/view?usp=sharing)

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

## RPP2 Provide Access to Assignment Repo

> Open at the beginning of class, **not prior to lecture**

1. Settings
2. Manage Access
3. Enter and Confirm your password
4. Invite teams or people (READ Access)
5. For RPP2, add **GalvanizeDataScience/21-02-ds-rpp**
6. For RPP2, Confirm: Add GalvanizeDataScience/21-02-ds-rpp

[* granting access to assignment repo how to video](https://drive.google.com/file/d/1UgR1OuQ_9dy9LSDXtgmXyxRhnAFqVEhH/view?usp=sharing)

## RPP2 Add Solutions to Cohort's Solutions Repo

[Galvanize Main Solutions Repo](https://github.com/GalvanizeDataScience/solutions)

^All the solution directories are here^

[RPP2 Solutions Repo](https://github.com/GalvanizeDataScience/solutions-rpp2)

^Only the solution directories that have been added for RPP2 are here^

> RPP2 opens solutions with assignment.   

> This will not be the case for RPP3. RPP3 solutions will be posted on the due date (I think).

ONLY DO THIS PART THE FIRST TIME YOU ADD SOLUTIONS:

RPP2 example: 

1. git clone https://github.com/GalvanizeDataScience/solutions-rpp2.git
2. cd into solutions repo
3. git remote add solutions https://github.com/GalvanizeDataScience/solutions.git
4. git fetch solutions main

DO THIS EVERY TIME YOU ADD SOLUTIONS:

1. cd into solutions repo
2. git pull
3. git fetch solutions main
4. git checkout solutions/main perceptrons
> using perceptrons as an example
5. git add .
6. git commit -m 'add perceptrons solutions'
7. git push

[* add solutions to cohort's solutions repo](https://drive.google.com/file/d/1-bMnSAy1uYL60b3aFw4e72U7_M1dByAN/view?usp=sharing)

## Daily Announcements  

Check-in with Instructor & PL prior to class regarding announcements 

## Post Lecture Recording After it Processes

[RPP2 Zoom Account](https://zoom.us/)

- edit recording name to include: *instructor, topic(s), date*
- check that no passcode is required


In a terminal, from the learn repo <dsi-learn-block>
```bash
git pull
git checkout RPP2
git pull (do we need to re-pull from each branch?)
code .
```
In VSCode: 
- Add lecture recording link.

- Save changes.

Back in terminal:

```bash
learn preview -o . #the -o opens a preview Learn block to see changes
git add .
git commit -m 'add lecture recording'
git push origin RPP2
```

From [RPP2 Learn](https://learn-2.galvanize.com/cohorts/2432)

1. **SET UP** tab
2. **Repos** tab
3. **<block_name>** block will have a green 'updates' oval
4. click sync arrows OR 3 vertical dots to right (choose update branch) of <block_name>  
5. Double check that the changes are working in the student facing Learn block.

[* add Zoom lecture recording to Learn how to video](https://drive.google.com/file/d/1HHMIrfLhJuhUm20fqOLfy-5EEF-cjxKJ/view?usp=sharing)

# Assessment Days 

## Opening Assessment in Learn 

TWO eyeballs to click!

From [RPP2 Learn](https://learn-2.galvanize.com/cohorts/2432)

1. **SET UP**
2. **Content** tab
3. **Assessments** block
4. **DSI Assessment #** click first eyeball
5. click dropdown arrow to left of **DSI Assessment #**
6. click second eyeball

[* opening assessments in Learn how to video](https://drive.google.com/file/d/1L_zHyMqH56RJAw6YmKtpJfbVEJH8JeJc/view?usp=sharing)

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

[* editing learn to add assessments solutions link how to video]()

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

[* add Zoom lecture recording to Learn how to video](https://drive.google.com/file/d/1HHMIrfLhJuhUm20fqOLfy-5EEF-cjxKJ/view?usp=sharing)

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
3. Open https://e21.ultipro.com/default.aspx
4. Choose Workforce Management tab
5. Use My Clock to clock in and out
6. Submit time sheet change requests as necessary

[* clock in/out + timesheet changes video](https://drive.google.com/file/d/1YSCi5f5xv8xA5YE6Mao7llonSldUH8J8/view?usp=sharing)



## Onboarding Stuff
Background check  
I9  
