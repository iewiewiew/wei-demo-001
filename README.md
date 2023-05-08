# wei-demo-001


# 测试@用户
```
git add . && git commit -m "@gitqa"


```


### 测试 Revert
```
git add . && git commit -m "dev 版本1"
git add . && git commit -m "dev 版本2"
git add . && git commit -m "dev 版本3"
git add . && git commit -m "dev 版本4"
git add . && git commit -m "dev 版本5"
git add . && git commit -m "dev 版本6 验证撤销最后一个提交并创建一个新的代码评审"
git add . && git commit -m "master 版本7"
git add . && git commit -m "master 版本8"
git add . && git commit -m "dev 版本9"
git add . && git commit -m "main 先回退还是合并再回退"
git add . && git commit -m "prem 先回退还是合并再回退"
```



### CI 环境
```
git add ci https://gitqa:qwe123@master.runjs.cn/testent001/wei-demo-001.git main  
git push -f https://gitqa:qwe123@master.runjs.cn/testent001/wei-demo-001.git main
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

test_admin@oschina.cn
test_admin123
http://backend-18628.premium-ci.cn/WTF/wei-demo-001.git
git push -f http://test_admin%40oschina.cn:test_admin123@backend-18628.premium-ci.cn/WTF/wei-demo-001.git main
```