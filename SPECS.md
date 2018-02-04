## Specification

# Modes:

 - hotfix
	- you can only modify no more than two files
	- you can’t create new files
	- you cannot change public classes interface
 - refactor
	- you can’t create new files
	- you cannot change tests
 - feature
	- you cannot modify any code
	 * __you cannot modify no more than 10 lines of code in total, enough to connect a new feature to the existing app__
	- all the code you create should go into one directory

# Running 

You can set this run constantly and punish you for mistakes, or only on pre-commit hooks. I would prefer the former.

	./check feature
	
# Todos:

 - automatically get MODE from branch naming
 - daemon
 - pre-commit hook

# Contributing

Welcome!


