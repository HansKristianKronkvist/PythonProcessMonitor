# Python Process Monitor
A python project that Monitors events on a Windows pc with WMI.

This program will track all events that occur while the program is running. It will track information such as path, PID, owner on system and enabled privileges (if there are any). It can be used both as an offensive and defensive tool in a way that an attacker can track after intriguing enabled privileges, and as a defender you can scan after programs running on the system. A csv file logging all the events will also be created so you can review the logs after running the program.

For this program you need to install the following package:
```
pip install wmi
```

This was built as an educational program to learn more about processes on windows and how to track them. 
