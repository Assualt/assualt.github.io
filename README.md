# assualt.github.io


## How to Build

```shell
$ hexo init hexo
$ git clone https://github.com/tufu9441/maupassant-hexo.git themes/maupassant
$ cd hexo && npm install hexo-renderer-pug --save
$ cd hexo && npm install hexo-renderer-sass --save
$ cd hexo && hexo server
## hexo -d 有点小问题,直接使用cp 操作进行拷贝到对应目录并提交到master
$ cd hexo && mv public/* ../ -f

$ git status 
```
