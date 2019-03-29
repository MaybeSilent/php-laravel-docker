## docker-compose 文件配置内容
php后端框架larravel在docker上的构建配置文件<br/>
配置了mysql+nginx+laravel
laravel框架下利用docker配置该内容，laravel框架连接该数据库的时候，DB_HOST文件应该填写phydb，否则会发生connect error
详情可见相关[issue](https://github.com/laradock/laradock/issues/178)
以及该[issus](https://github.com/shipping-docker/vessel/issues/13)
