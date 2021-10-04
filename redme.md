gcc server.c -o server

i686-w64-mingw32-gcc -o malware.exe backdoor.c -lwsock32 -lwininet


persist


HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Run
