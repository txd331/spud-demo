# spud-demo
Spud Grails Demo Application
## test
程序结构图
```flow
  theme(通用模块)
   App[appModule] -->page[pageModule]
    App-->auth[auth]
    page --> search[搜索]
    page -->warn[预警]  
    page -->sta[统计] 
search-->doc[详细页面]
warn-->doc[详细页面]
sta-->doc[详细页面]
```
||~head1||~head2||~head3||~head4||
|| || || || ||
|| || || || ||
|| || || || ||
