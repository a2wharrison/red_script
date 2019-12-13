# red_script
Python Script that will snag Port, IP, PID, Executable Name, User ( Root or Sudo ), Title

Install on any machine in the house and just run it through cmd for 24 hours and we can check the output from there..

- cmd..
- cd to the directory the file is in
- run python /user/file/location red_script.py

Run for 1 hour and check the log file in the same directory

adjust the code or let me know and can adjust it for you


Example output

Port  RemoteIP  PID     Executable Name         User           Title
=====================================================================
80    0.0.0.0   14232   Skype.exe               Desktop\User   N/A
81    0.0.0.0   1836    httpd.exe               N/A            N/A
135   0.0.0.0   388     svchost.exe             N/A            N/A
443   0.0.0.0   14232   Skype.exe               Desktop\User   N/A
444   0.0.0.0   1836    httpd.exe               N/A            N/A
445   0.0.0.0   4       System                  N/A            N/A
554   0.0.0.0   5504    wmpnetwk.exe            N/A            N/A
1170  0.0.0.0   7124    PlexDlnaServer.exe      Desktop\User   N/A
2869  0.0.0.0   4       System                  N/A            N/A
2968  0.0.0.0   5936    EEventManager.exe       Desktop\User   Epson Event Manager Background
4242  0.0.0.0   2092    CrashPlanService.exe    N/A            N/A
5357  0.0.0.0   4       System                  N/A            N/A
