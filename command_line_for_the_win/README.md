## sftp username@host
* username@host's password: ******************
* ___Connected to host___
## sftp> ls
```shell
alx     bin     boot    dev     etc     home    lib     lib32   lib64   libx32  media   mnt     opt     proc    root    run     sbin    srv
sys     tmp     usr     var
```
## sftp> ls alx/alx-system_engineering-devops/command_line_for_the_win/
## sftp> cd alx/alx-system_engineering-devops/command_line_for_the_win/
## sftp> pwd
```shell
Remote working directory: /alx/alx-system_engineering-devops/command_line_for_the_win
```
## sftp> put ./0-first_9_tasks.png
```shell
Uploading ./0-first_9_tasks.png to /alx/alx-system_engineering-devops/command_line_for_the_win/0-first_9_tasks.png
./0-first_9_tasks.png                                                                                             100%   46KB  30.1KB/s   00:01
```
## sftp> put ./1-next_9_tasks.png
```shell
Uploading ./1-next_9_tasks.png to /alx/alx-system_engineering-devops/command_line_for_the_win/1-next_9_tasks.png
./1-next_9_tasks.png                                                                                              100%   82KB  15.6KB/s   00:05
```
## sftp> put ./2-next_9_tasks.png
```shell
Uploading ./2-next_9_tasks.png to /alx/alx-system_engineering-devops/command_line_for_the_win/2-next_9_tasks.png
./2-next_9_tasks.png                                                                                              100%   64KB  14.7KB/s   00:04
```
## sftp> pwd
```shell
Remote working directory: /alx/alx-system_engineering-devops/command_line_for_the_win
```
## sftp> ls
```shell
0-first_9_tasks.png  1-next_9_tasks.png   2-next_9_tasks.png
```
## sftp> exit

      ~/a/alx-system_engineering-devops/command_line_for_the_win     master ?1                                               ✔  1m 52s    
