## Creating your site with Jemdoc

- run the following command in the source folder. 
- `python2 jemdoc -c mysite.conf -o ../ *.jemdoc` 


## Steps to setup Python2 

1. install homebrew: https://brew.sh, as instructed on the website: 
   - `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
2. install python2 through brew by typing the following command in the terminal: 
   1. `brew install pyenv`
   2. `pyenv install 2.7.18`
   3. `pyenv global 2.7.18`
   4. `export PATH="$(pyenv root)/shims:${PATH}"`
   5. `echo 'PATH=$(pyenv root)/shims:$PATH' >> ~/.zshrc`
3. check if the python2 is installed by typing: `python2 --version`