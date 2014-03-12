Installation:

-Ensure Coreutils is installed for **gls**
```	
brew install coreutils
mkdir ~/.dircolors
git clone https://github.com/gibbling666/dircolors.git ~/.dircolors
```

Setup:


	Add the following to ~/.bash_profile
	
	# ~/.dircolors/themefile
	eval $(gdircolors ~/.dircolors/dircolors.256dark)

	# Aliases
	alias ls='gls --color=auto'
	alias ll='ls -al'

Notes:

-Please check out solarized dircolors here https://github.com/seebi/dircolors-solarized

