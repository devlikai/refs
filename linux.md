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
