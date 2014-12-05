My Dot Files


``` 
# Make a directory:
mkdir ~/bin

# Change directory into new directory:
cd ~/bin

# Git clone this repo:
git clone git://github.com/alysonla/dotfiles.git

# Create a file called .bashrc:
touch ~/.bashrc

# Add the thing in the quotes to the .bashrc file:
echo ". ~/bin/dotfiles/bashrc" >> ~/.bashrc

# Create a file called .bash_profile:
touch ~/.bash_profile

# Add the thing in quotes below to the .bash_profile file:
echo ". ~/.bashrc" >> ~/.bash_profile

# Open .bash_profile:
. ~/.bash_profile
```
