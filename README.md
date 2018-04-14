## introduction

a simple nodejs script used for grabing ip location from http://ip.taobao.com

## usage

```
## save ip information into ip.txt and errors into err.txt
## DO **NOT** need to care about error, it will retry the 
## same addr when error occurred

$ npm install
$ ./crawler > ip.txt 2>/dev/null
```
