# Note
一些问题的笔记
  1.discuz无法连接远程mysql库，报出Can't connect to MySQL server on  ip (13)这种错误的时候
    可执行 以下解决 setsebool -P httpd_can_network_connect_db=1
