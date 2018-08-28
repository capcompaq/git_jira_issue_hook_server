# git_jira_issue_hook_server
在服务器端判断开发人员推送的代码日志是否包含jira问题单号

# 脚本用于服务器端的git hook目录
这里使用的Python，请将脚本放入git服务器端的hooks目录，修改对应的权限<br>
chown -R git:git hooks<br>
chown -R git:git pre-receive<br>
chmod 755 pre-receive<br>
保证脚本可以执行<br>
