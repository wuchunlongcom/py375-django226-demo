python3.7.5   django2.2.6  部署正常                      

### 功能：部署正常的demo。 
      
```
一、 运行      
1、运行：./start.sh 

二、 后台超级用户登录
用户名/密码  
admin/admin

三、用户登录
http://localhost:8000/
```

```
import-admin
注意：1、上传git, 删除env(python3.7.5)；
     2、./start.sh -i   要保证env(python3.7.5)在工程中；
     3、本工程的 env(python3.7.5)与requirements.txt 必须配合使用；
     4、一个工程一个虚拟环境是必须的，否则容易产生本机运行正常，部署却不正常的问题。
```
