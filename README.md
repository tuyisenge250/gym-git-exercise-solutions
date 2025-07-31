# Gym Git Exercise Solutions

# bundle 1

# Exercise 1

 mkdir bundle1exercise1

 1997  cd bundle1exercise1

 1998  git init

 1999  echo helloworld >> script.js

 2000  git branch -m main master

 2001  git branch

 2002  git add .

 2003  git commit -m"bundle1 exercise 1"

 2007  git status

 2008  echo codingcureer >> script.js

 2009  git branch main

 2010  git branch

 2011  git branch -d main

 2012  git branch -m master main

 2013  git remote add orgin https://github.com/tuyisenge250/bundle1exercise1.git

 2014  git push

 2015  git push --set-upstream origin main

 2016  git branch dev

 2017  git checkot dev

 2018  git checkout dev

 2019  git checkout -b test

 2020  git branch

 2021  git checkout dev

 2022  git branch -m test
 
 2023  git branch -d test

 # Exercises 2

 echo home.html

 1995  echo >home.html

 1996  git status

 1997  git init

 1998  git status

 1999  git stash -u

 2003  git add .

 2004  git stash

 2007  git stash -u

 2008  echo >team.html

 2009  git stash -u

 2010  git stash list

 2011  git apply stash@{1}

 2012  git stash apply stash@{1}

 2013  git stash list

 2014  git stash drop stash@{1}

 2015  git stash list

 2016  git stash pop stash@{1}

 1990  git add .

 1991  git commit -m"hundle1exercise2"

 1992  git push
 
 1995  git stash pop

 1996  git status

 1997  git stash list

 1998 git resort team.html

 # bundle 2
 # exercises 1

 1987  git branch ft/bundle-2 

 1988  git branch

 1993  git checkout ft/bundle-2

 1994  echo >services.html

 1995  git add .

 1996  git commit -"change in ft/bundle-2"

 1998  git commit -m"change in ft/bundle-2"

 1999  git push

 2000  git push --set-upstream origin ft/bundle-2

# exercises 2

 2006  git checkout main

 2007  git pull

 2008  git config --global pull.rebase false

 2009  git pull

 2010  git checkout ft/service-redesign

 2011  git checkout -b ft/service-redesign

 2012  git add .

 2013  git commit -m"bundle2exercises2"

 2014  git push

 2015  git push --set-upstream origin ft/service-redesign

 2016  git checkout main

 2017  git commit -am"change at main"

 2018  git push

 2019  git checkout ft/service-redesign

 2020  git add .

 2021  git commit -m"new to hundle2exercise2"

 2022  git checkout main

 2023  git pull

 2024  git stash services.html

 2025  git add .

 2026  git commit -m"the change"

 2027  git pull

 2028  git push

 2029  git checkout ft/service-redesign

 2030  git status

 2031  git log

 2032  git push

 2033  git checkout main

 2034  git status

 2035  git commit -am"conflit"

 2036  git push

 2037  git checkout ft/service-redesign
 
 2038  git diff

 2039  git diff --branch

 2040  git diff main

 2041  git checkout main

 2042  git merge ft/service-redesign

 2043  git add .

 2044  git commit -m"merged and conflit resolved"
 
 2045  git push
