# docker-log

This is demo project based on 
 - official image nginx 
 - custom build of rsyslog **panoptix/rsyslog

##USAGE
####START
**docker-compose up -d**
**curl localhost 80 ** this command will request web page on nginx and access log will be transfered to the main log server
####STOP
- **docker-compose down

**Change name of main logging server we can at file logentries.conf**
