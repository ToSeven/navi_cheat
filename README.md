# navi_cheet
## example

```code
% git, code
# Change branch
git checkout <branch>
$ branch: git branch | awk '{print $NF}'
```
Cheatsheets are described in .cheat files that look like this:  
* lines starting with % determine the start of a new cheatsheet and should contain tags, useful for searching;
* lines starting with # should be descriptions of commands;
* lines starting with ; are ignored. You can use them for metacomments;
* lines starting with $ should contain commands that generate a list of possible values for a given argument;
all the other non-empty lines are considered as executable commands.
It's irrelevant how many files are used to store cheatsheets. They can be all in a single file if you wish, as long as you split them accordingly with lines starting with %.
