
# SSM login into the multiple servers using AWS cloudshell

This script can be used to login into the multiple servers using AWS cloudshell.

The "execute.sh" is a bash file that will be switching between the AWS regions to run "script.py".

The script (script.py) will find all the servers that name has the substring provided in a region and try to create a session with the server. The final output will be displayed on the terminal and a output file will be genrated (output.txt)
## Execution

```Bash
cd SSM-Login-EC2 
chmod 777 execute.sh script.py
./execute.sh
```


## Screenshot

![App Screenshot](https://i.postimg.cc/0jm7LSWG/Screenshot-from-2024-03-12-10-02-51.png)

![App Screenshot](https://i.postimg.cc/SRyyhFVZ/Screenshot-from-2024-03-12-10-09-44.png)
