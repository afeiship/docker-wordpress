# docker-wordpress
> Docker for wordpress.

## setting
```shell
## php5-fpm默认属于www-data用户组，但是其权限很低，比如不能创建文件夹，所以需要对其授权
## sudo chown -R www-data:www-data
cd docker-wordpress
sudo chown -R www-data:www-data ./data/wp_data/wp-content
````
![](https://ws4.sinaimg.cn/large/006tNc79ly1g2kmny2qhuj30iz04fwf7.jpg)

## preview
- http://localhost:9001/

## resources
- https://qiita.com/vc7/items/e88026c75f2280f95ed4
- https://github.com/docker-library/wordpress/issues/298