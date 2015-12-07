Hey,

Setup for flint

1. Install node (5.1 is stable atm) - https://nodejs.org/en/
2. Install git
  2a. Install http://brew.sh/ `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
  2b. `brew install git`
3. See instructions on flint in chat
4. Install surge

Instructions to deploy your app (in terminal)

1. cd ~
2. mkdir projects
3. cd projects
1. git clone git@github.com:natew/arena.git
2. cd arena
3. flint build
4. cd .flint/build
5. surge

Surge.sh guys do a good job with simple hosting for not too much $. Check them out for how to use them, it's really simple.
