# GitCompletion4Mac
GitCompletion is create for mac to help those who use git command in terminal.

#How to use it?
1. clone the git repository
2. cp git-completion.sh ~/.git-completion.sh
3. open ~/.bash_profile(if not exist, just create one)
4. add "source ~/.git-completion.sh" at the end of .bash_profile
5. restart the terminal and it will works.


#Other Tips
(1)Get new colorful git log in terminal

  excute this command in terminal: 
    
    git config --global alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --"
    
  then use 'git lg' instead of 'git log'

