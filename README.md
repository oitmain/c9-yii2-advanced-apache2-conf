# C9 Apache 2 configuration for Yii2 Advanced App

This configuration will run yii2 advanced app in multiple ports, `8081` for frontend and `8082` for backend.

Yii2 mustbe installed on `/home/ubuntu/workspace/yii2-advanced` or modify the configuration files.

```sh
sudo ln -s $(pwd)/002-front.conf /etc/apache2/sites-enabled
sudo ln -s $(pwd)/003-backend.conf /etc/apache2/sites-enabled
```
