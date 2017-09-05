# gitAutoPush
This project automates the pushing and commiting of git for those times where you are in a hurry and forget.
There are two main cases that this project aims to take care of.

1. User forgets to make commits or push existing commits before shutting down their computer.
  Requirements: <br/>
  -Program should push all pending commits. <br/>
  -Program should then attempt to make a commit for changes that have not yet been commited (possibly including new untracked files). <br/>
  -If there are conflicts program should halt shutdown process and get user input on how to deal with commit issues. <br/>
  -Program should push commits.

2. User forgets to make commits or push existing commits before leaving for somewhere. 
  Requirements: 
  -Program should have either a schedule or an inactivity timeout.<br/>
  -Program should then attempt to make a commit for changes that have not yet been commited (possibly including new untracked files). <br/>
  -If there are conflicts program should halt shutdown process and get user input on how to deal with commit issues. <br/>
  -Program should push commits.
