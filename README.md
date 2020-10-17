# Lab-06
## Exercise 1 - Pull and Push (different branches)
### Overview
In this exercise, make changes and push them

#### <u> Cloning a repo </u>
- Go to a playground folder using explorer (c:\temp, for example)
- Right click inside the folder and select 'GitExt Clone...'
- Paste the URL https://MBTURLLab06-ex1.git and choose clone
- Right click inside/on the folder and select 'GitExt open repository'

#### <u> Create branch and commit </u>
- On left pane, select <i>master</i> branch, right click it, and select 'Create Branch'
- Name the branch as yourname (for example: noamamrani) and press 'Create Branch'
- Make a change to <i>Readme.md</i> using your favorite editor outside of GitExtension
- Commit your changes
    1. On the Button Bar, Press the Commit icon
    2. Add the relevant files to stage using the purple arrows (stage/unstage)
    3. Add any explaining message
    4. Click commit

#### <u> Push your branch </u>
- Checkout your branch
- On the Button Bar, click <i>Push</i> button, leave defaults and click <i>Push</i>

## Exercise 2 - Pull and Push (same branch)

#### <u> Cloning a repo </u>
- Go to a playground folder using explorer (c:\temp, for example)
- Right click inside the folder and select 'GitExt Clone...'
- Paste the URL https://MBTTFS/Lab06-ex2.git and choose clone
- Right click inside/on the folder and select 'GitExt open repository'

#### <u> Making changes </u>
- On the left pane, right click <i>Remotes -> Origin -> master</i> branch and select <i>Fetch & Merge</i>. This will create our local master branch. Press <i>Merge</i> if required.
- Add your name to the README.md file
- Commit your changes (locally)
    1. On the Button Bar, Press the purple Commit icon
    2. Add the relevant files to stage using the purple arrows (stage/unstage)
    3. Add your name in the message
    4. Click commit

#### <u> Push master branch </u>
- Checkout master branch
- Since other people are working on the master, first we need to pull:
- On the left pane, right click <i>Remotes -> Origin -> master</i> branch and select <i>Fetch & Merge (Pull)</i>. This will create our local <i>master</i> branch. Press <i>Merge</i> if required.
- Since all are working on the same branch, there might be conflicts, if so, please 
    - Resolve conflicts as we did in Lab04, conflicts.
    - Commit your changes once done
- On the Button Bar, click <i>Push</i> button, leave defaults and click <i>Push</i>

