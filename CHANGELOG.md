ESP ChangeLog
============

Pending Commit
--------------
 * Implemented New configuration option system
 * Configuration option to call SSP automaticaly, however SSP is still disabled by default
 * Replaced history line number with the ticket number [#10]
 * Added checks to test if the mailserver process is dead
 * Addded check to check for cPanel and display 10 sec warning if cPanel is not detected [#13]
 * Added check for vim and sets that as the editor,  if vim is non-existant, it falls back to vi and creates an alias for vim to vi. [#22] 

Feb 9, 2014
-----------
 * Removed mysqltuner becuse it is out of date and is being pulled from cPanel in case 90317
 * Add Change Log [#16]

Feb 6, 2014
-----------
Inital Commits
