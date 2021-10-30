git config

```bash
git config --global user.name "lonelymoon"
git config --global user.email "lonelymoon@aliyun.com"
git config --list
git config --global http.proxy http://127.0.0.1:1080
git config --global https.proxy http://127.0.0.1:1080
```

普通操作

```bash
git init
git add .
git commit -m "message info"
git remote add origin {shh or http address}
git remote -v
git push -u origin master
```

#### 解决Git中fatal: refusing to merge unrelated histories

只用在命令后面加上 --allow-unrelated-histories即可

```bash
git pull origin master --allow-unrelated-histories
```

