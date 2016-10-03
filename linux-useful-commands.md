# Linux commands

### Process and network

* netstat – displays network connections, routing tables, and a number of network interface statistics.

`netstat -tulpn [ | grep :80 ]`

* fuser – identifies processes using files or sockets.

`fuser 7000/tcp`

* lsof – reports a list of all open files and the processes that opened them.

`lsof -i :80 [ | grep LISTEN ]`

Kill a process on a specific port: `kill $(sudo lsof -t -i:$PORT)`
