# check-check
  每天自动签到（天数+1），自动推送结果  


# Github Actions说明
## 一、设置账号密码

添加名为——值分别为：  
**SERVE**  ——**on/off** 你想你的serve酱开不开启通知  
**SCKEY**  ——**sckey**  开的话填你的serve酱的sckey，不开就不填   
**COOKIE** —— **cookie** 弄上你账号的cookie  
暂不支持多账号，懒得弄
![](http://tu.yaohuo.me/imgs/2020/06/748bf9c0ca6143cd.png)

## 二、启用Action
1 点击**Action**，再点击**I understand my workflows, go ahead and enable them**  
2 修改任意文件后提交一次  
![](http://tu.yaohuo.me/imgs/2020/06/34ca160c972b9927.png)

## 三、查看运行结果
Actions > Cloud189Checkin > build  
  
此后，将会在每天半夜12点多会自动签到一次  
若有需求，可以在[.github/workflows/python-publish.yml]中自行修改  
