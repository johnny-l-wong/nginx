
# 检查80端口使用情况： netstat -aon|findstr ":80"
# 启动并指定配置文件： nginx -c conf/nginx.conf
# 验证配置是否正确: nginx -t
# 查看Nginx的版本号：nginx -V
# 启动Nginx：start nginx
# 快速停止或关闭Nginx：nginx -s stop
# 正常停止或关闭Nginx：nginx -s quit
# 配置文件修改重装载命令：nginx -s reload
# 列出nginx任务列表： tasklist /fi "imagename eq nginx.exe"