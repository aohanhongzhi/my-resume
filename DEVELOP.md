部署
===

## 更新在线简历

```shell
scp index.html eric@houxiaoyi.cn:/media/data/eric/docker/nginx/www/html
```

## 更新pdf简历
```shell
scp 侯小益简历20.8.pdf  eric@houxiaoyi.cn:/media/data/eric/docker/nginx/www/html
```

## 更新样式

```shell
scp -r assets/ eric@houxiaoyi.cn:/media/data/eric/docker/nginx/www/html
```
### 上传图片
```shell
scp  assets/images/IMG_20210209_203748.jpg eric@houxiaoyi.cn:/media/data/eric/docker/nginx/www/html/images
```

```shell
scp  assets/images/link-999.svg  eric@houxiaoyi.cn:/media/data/eric/docker/nginx/www/html/assets/images
```


## element-ui样式

https://unpkg.com/browse/element-ui@2.15.6/lib/theme-chalk/fonts/
