Hey,

Setup for flint

1. Install brew
  - `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
2. Install git
  - `brew install git`
3. Install nvm + node
  - `brew install nvm`
  - `nvm install 5`
4. Install flint (see site)
4. Install surge
  - `npm install -g surge`

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
