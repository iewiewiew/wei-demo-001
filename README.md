# wei-demo-001


### 测试 Revert
```
第一次
第二次 
第三次
第四次
git add . && git commit -m "第11次"
```



### CI 环境
```
git add ci https://gitqa:qwe123@master.runjs.cn/testent001/wei-demo-001.git main  
git push -f https://gitqa:qwe123@master.runjs.cn/testent001/wei-demo-001.git main  --no-verify
git pull -f https://gitqa:qwe123@master.runjs.cn/testent001/wei-demo-001.git main  
git push -u ci main  
git add . && git commit -m "test"  
```


### premium 环境
```
https://premium-k8s.gitee.cn/login
gitee@oschina.com
oschina123
https://premium-k8s.gitee.cn/fenbushianzhuangbaoceshi/wei-demo-001.git
git push -f https://gitee@oschina.com:oschina123@premium-k8s.gitee.cn/fenbushianzhuangbaoceshi/wei-demo-001.git main
git push -f https://gitee%40oschina.com:oschina123@premium-k8s.gitee.cn/fenbushianzhuangbaoceshi/wei-demo-001.git main
git push -f prem main
```