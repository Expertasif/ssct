# ShadowSocks ConnecTion
A wrapper tool for shadowsocks to consistently bypass firewalls.
```
ssct options:  
  -n <num>           connect server number  
  --ss <ss>          path to shadowsocks, assumed in the PATH  
  --list             list all ss servers  
  --stop             stop running servers  
  --version          show program's version number and exit  
  -h, --help         show this help message and exit  
  --morehelp         show more help message and exit  

shadowsocks options:  
  -c <config>        path to config file  
  -s <addr>          server address, auto crawl online  
  -p <port>          server port, auto crawl online  
  -b <addr>          local binding address [default: 127.0.0.1]  
  -l <port>          local port [default: 1080]  
  -k <password>      password, auto crawl online  
  -m <method>        encryption method, auto crawl online  
  -t <timeout>       timeout in seconds [default: 300]  
  --fast-open        use TCP_FASTOPEN, requires Linux 3.7+  
  -d <daemon>        daemon mode, one of start, stop and restart  
  --pid-file <file>  pid file for daemon mode  
  --log-file <file>  log file for daemon mode  
  --user <user>      username to run as  
  -v, -vv            verbose mode  
  -q, -qq            quiet mode, only show warnings/errors  
```
Connect to the available server automatically without any argument.
