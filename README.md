# 基于 MFC 与 `txt` 文件交互、在 vs2017 上开发出的图书管理系统。
  已附带 $13$ 万本左右的图书。
  
  使用前需更改 `loging.rc` 中的图片文件路径，否则程序就会运行出错。
  
  此程序主要有登录界面、图书管理与用户管理界面三个模块。
  
  其中的字符串搜索算法是完全的暴力，没有使用到正则表达式。因为重点的思考都放在了学习 MFC 上。总体上，这个程序极其简陋。
  
  作者支持任何对优化算法的想法的提出。如果仅是为了求资源而来，请不要直接拿去当作业上交（就算要上交也需要调整调整）。

```c
/**
  * This is a pretty plain project of library-management-system implemented by MFC.
  * Attached a dataset containing 130,000+ books' information.
  * Anyone Should rewrite <the absolute path of the img file> that has been coding in loging.rc, line 79 and line 549, which seems to be located at the position.
  * Otherwise the program will fail.
  * Roughly the program  included 2 interface: loging interface, (users and books) management interface. 
  * The algorithm can't be worse anymore since the task is limited in 7 days and most of time, the author points to learn how MFC works.Hence the exe is very very simple.
  *
  * Any crazy ideas about optimizing this program are highly welcome. Don't need to be hesitated.
  **/
```
  
  
