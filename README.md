# Bears-Team-11
Add-project-description-here | Voyage-7 | https://chingu.io/

### Setup
1. Clone the repo - ```$ git clone git@github.com:chingu-voyage7/Bears-Team-11.git```
2. The repo defaults to the development branch. If you're not on that branch, switch - ```$ git checkout development```
3. Switch to your feature/working branch
    * When creating a new branch:
        * ```$ git checkout -b feature-addTime-#12-jon```
        * this will create the branch and immediately switch to that branch
    * When switching back to an existing branch:
        * ```$ git checkout feature-addTime-#12-jon```

### Working with Git and Github
1. Switch to development (only when you're not on that branch) - ```$ git checkout development```
2. ```$ git pull origin development``` from development before you start coding (all the time)
3. Switch to your feature/working branch
    * Naming your branch (consists of 4 parts):
        1. issue type (feature, bug, style, refactor)
        2. issue name
        3. waffle card #
        4. your name
    * Separate the 4 parts with dashes
    * Use camel case for parts that are more than 2 words
    * Example
        * ```feature-addTime-#12-jon```
4. Merge the new code - ```$ git merge origin development```
5. Make commits often
6. Push to GitHub when you are done with your feature - ```$ git push origin <feature-branch>```


### Pull Requests
1. Go to Github, look for your pushed branch, and issue a Pull Request (PR)
2. Select a team member to review the code

### Merging PRs (reviewer)
1. Look for the PR
2. Make sure that the branches selected are the development branch and a feature branch
3. Compare the changes 
4. Fix any conflicts (send back to dev if needed)
5. Merge if no conflict exists
