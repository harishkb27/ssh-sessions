# ssh-sessions

ssh-sessions is a simple script that lists running ssh sessions in your system and presents you with an option menu to ssh into any of the servers from the list of existing sessions. It can be seen as a simple time saver during times when multiple ssh connections to the same server are required.

## usage

Just run the script like any other linux executable. Also, you can add this script (path) to your system PATH.

### example

```sh

$ ssh-sessions 
1) ssh ubuntu@server1
2) ssh -i ~/.ssh/test.pem ubuntu@server2
Select the menu number to ssh:1
ubuntu@server1:~$
ubuntu@server1:~$ exit
logout
Connection to server1 closed.

```

License
----

MIT


**Free Software, Hell Yeah!**
