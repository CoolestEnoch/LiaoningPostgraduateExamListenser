# 辽宁考研准考证和考场公开信息自动化查询器




# ***⚠️⚠️当下面两个都红了就可以下载准考证了⚠️⚠️***<br/>
考场查询：[![LiaoningExamWindow](https://github.com/CoolestEnoch/LiaoningPostgraduateExamListenser/actions/workflows/LiaoningExamWindow.yml/badge.svg)](https://github.com/CoolestEnoch/LiaoningPostgraduateExamListenser/actions/workflows/LiaoningExamWindow.yml)<br/>
准考证下载：[![YanZhaoWang](https://github.com/CoolestEnoch/LiaoningPostgraduateExamListenser/actions/workflows/YanZhaoWang.yml/badge.svg)](https://github.com/CoolestEnoch/LiaoningPostgraduateExamListenser/actions/workflows/YanZhaoWang.yml)




## 原理：
每十分钟运行一次workflow,当可以下载准考证或者考场信息的时候run fail并发送邮件到github绑定的邮箱里实现通知作用。
当发送邮件后，会自动禁用workflow（通过对其schedule字段注释来实现）。如果要重新启用，则将注释删除即可。




## 用法：
搞一个github personal access token (PAT), 仓库操作权限都给，可以是只作用于这个仓库而不是全局的，将token复制，黏贴到本仓库的secrects的PAT_TOKEN里，然后启用本仓库的actions,慢慢等就ok



## 相关链接
[辽宁招生考试之窗查询中心](https://www.lnzsks.com/cxzx.html)
[研招网网报流程状态查询](https://yz.chsi.com.cn/yzwb/)
