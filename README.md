### Notes
1. <code>::</code> and <code>REM</code> are used to add comments in a .bat file  
2. <code>pause</code> pauses execution of the script and waits for the user to hit any key  

### syncTime.bat script
- I wrote this script to synchronize time on my Windows7 computer.
- The first 24 lines (taken from [this stackoveflow discussion](https://stackoverflow.com/questions/11525056/how-to-create-a-batch-file-to-run-cmd-as-administrator)) were included to make the batch file run cmd as admin. If not already in the admin account, a window for the admin password will pop up.
- Without the <code>/force</code> parameter on line 27, sometimes see this error:
<i>The computer did not resync because the required time was change to big</i>

### Batch script resources:  
https://www.tutorialspoint.com/batch_script/index.htm  
https://www.howtogeek.com/263177/how-to-write-a-batch-script-on-windows/  

