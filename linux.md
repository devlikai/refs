# 故障排查，日志追踪
tail -f -n 

| wc -l

| tee text.txt

ls -al
文件列表，文件大小为字节，ll不是命令，而是ls -l的别名
ls -alh 通常会加参数h来直观显示大小，会使用G、M等来显示大文件

sed

awk

ps -ef | grep tomcat

netstat -anlp| grep

正则表达式

^  :  行起始标志， 例如：^ben 表示匹配以ben开始的行。

$  :  行结尾标志。例如：ben$ 表示匹配以ben结束的行。

[^] ：匹配除[^字符]之外的任何一个字符。 例如9[^0]， 不会匹配90，但是会匹配91,92等。

网络相关：
ping
telnet ip port
curl
  -X
  -v
  -k
