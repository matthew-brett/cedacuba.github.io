#############################
Working on the course website
#############################

In ``cmd`` shell::

    cd c:\Users\valia\la-eeg-uci

To get all the latest changes from github::

    git pull

To see what needs to be done

    git status

Change what you want to change in the ``c:\Users\valia\la-eeg-uci`` folder.

Check what changes you have made to the files with::

    git diff

Check how the changes will look with::

    make html

Then open the address
``file://C:/Users/valia/la-eeg-uci/_build/html/index.html`` in the web browser
to see the website as it will look when pushed to github.

When you're happy with the changes, check them again::

    git diff

If they all look OK::

    git commit -a -m "Your message about the changes"

Send these changes to the source files up to github::

    git push

To publish the new changed files up to the website::

    make github
