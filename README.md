This Repository is mainly focusing the basic of git overview and git commands.
Learn about daily use commands.

# To create a new branch
Example: create a new branch branchdemo from origin/main:
commands:
         git checkout main
         git checkout -b branchdemo #creates a new branch branchdemo from origin/main.
                                    #It creates branch in local, it will be not reflecting in github.
         git push --set-upstream origin branchdemo
         


