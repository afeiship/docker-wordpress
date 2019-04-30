# docker-wordpress
> Docker for wordpress.

## get-started
```shell
# common manngeent
./bin/start.sh
./bin/stop.sh
./bin/restart.sh

## be careful!!!
./bin/reset.sh
```

## setting
~~~
cd docker-wordpress
sudo chown -R www-data:www-data ./data/wp_data/wp-content
~~~
![](https://ws1.sinaimg.cn/large/006tNc79ly1g2kmjygnc0j30iz04fglq.jpg)

## preview
- http://localhost:9001/

## resources
- https://qiita.com/vc7/items/e88026c75f2280f95ed4
- https://github.com/docker-library/wordpress/issues/298