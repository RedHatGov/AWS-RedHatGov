# Git Pre-commit 

This script checks to make sure you are not commiting your AWS API keys into GitHub. [Bad things](http://www.theregister.co.uk/2015/01/06/dev_blunder_shows_github_crawling_with_keyslurping_bots/) happen when you put AWS API keys in GitHub. 

Copy this file to `~/.git-templates/hooks/pre-commit`

If a AWS API key is inthe directory you are commiting, this script will warn you. 
