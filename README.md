C9.io Apache 2 configuration for Yii2 Advanced App
===============================
This configuration will run yii2 advanced app in multiple ports, `8081` for frontend and `8082` for backend.
```sh
YII_FOLDER=/home/ubuntu/workspace/warehouseabc-pdf
sed -i -e "s~:yii_folder~${YII_FOLDER}~g" *.conf
sudo ln -s $(pwd)/002-front.conf /etc/apache2/sites-enabled
sudo ln -s $(pwd)/003-backend.conf /etc/apache2/sites-enabled
```
