# Ratfly.github.io
Hello Github.io
###在windows下，查看java进程信息
在windows下，有些java服务是以系统服务的形式启动的，启动的服务在任务管理中进程名称只是简单的显示为java.exe，所以通过任务管理中看出具体是哪个服务是不太可能的，还占用较大系统资源，这时关闭进程后又自动出现，有时还以为是病毒或者是其他什么呢。这时就可以通过jdk自带的工具jinfo来查看相应的信息，不过因为以系统服务启动的，对应的用户是system，所以启动金佛需要以管理员的身份运行才能查看相应信息，否则会报：Error attaching to process: Windbg Error: WaitForEvent failed的错误。
