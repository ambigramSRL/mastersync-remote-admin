# mastersync-remote-admin
keep linux servers in sync... an easy open solution for linux administrators

Found on linked in, all started with this question

"How to run remote command on a lot of servers at the same time

Dears , How to run a same remote command on 1000 servers or more at once and store the output on one file on your local machine without using 3rd party APP. ?

if we are using "ssh" in "for" loop, it will take a lot of time, is there any other way to run the remote command on all servers at the same time ?"
Thank you Ahmed Gamil ( https://www.linkedin.com/profile/view?id=ADcAAAxrJrsB06C7UxpXAb_5z6dM9ciwXhBpwms&authType=name&authToken=EHq0 ) for asking.

From that, an ideea was arised... what if we can use existing powerfull tools in order to perform such a task ?
What is the best way to scale ?
Our idee is that every server can act as clients for a central server that send message to 

Remote Servers can 
1. be listed individual
2. be part of groups
3. notify about conditions the central admin panel
4. upgraded, etc.

No need to ssh into, just old plain https based messaging - but also a realtime and lowlatency operation can be imagined.

Why not let a station be also managed ? We see no reason not to do that.

So here we go...
