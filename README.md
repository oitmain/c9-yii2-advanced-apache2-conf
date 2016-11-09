Run yii2 advanced app in multiple ports. 

8081 for frontend and 8082 for backend

sudo ln -s $(pwd)/002-front.conf /etc/apache2/sites-enabled
sudo ln -s $(pwd)/003-backend.conf /etc/apache2/sites-enabled