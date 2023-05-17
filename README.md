# wei-demo-001


### CI 环境
```
git add ci https://gitqa:qwe123@master.runjs.cn/testent001/wei-demo-001.git main  
git push -f https://gitqa:qwe123@master.runjs.cn/testent001/wei-demo-001.git main
git push -f https://gitqa:qwe123@master.runjs.cn/testent001/wei-demo-001.git main  --no-verify
git pull -f https://gitqa:qwe123@master.runjs.cn/testent001/wei-demo-001.git main  
git pull -f hightest main  
git push -u ci main  
git add . && git commit -m "test" 
```


### premium 灰度环境
```
https://premium-k8s.gitee.cn/ 
账号：gitee@oschina.com
密码：oschina123

https://premium-k8s.gitee.cn/fenbushianzhuangbaoceshi/wei-demo-001.git
git push -f https://gitee@oschina.com:oschina123@premium-k8s.gitee.cn/testent001/wei-demo-001.git main
git push -f https://gitee%40oschina.com:oschina123@premium-k8s.gitee.cn/testent001/wei-demo-001.git main
git push -f prem main
```


### 其它
```
cd wei-demo-001
git remote add pre_gray https://premium-k8s.gitee.cn/testent001/wei-demo-001.git
git push -u pre_gray main
```



