#Копируем репозиторий
```
git clone https://github.com/VaultdVellerDao/flaskBlog
```
#Устанавливаем Certbot
```
sudo apt install certbot python3-certbot-nginx
```
#Выпускаем SSL 
```
sudo certbot --nginx -d test-devops.vizorlabs.tech -d test-devops.vizorlabs.tech
```
#Запускаем приложение
```
docker compose up -d 
```

#Резервное копирование
>Зайти в директорию приложения и запустить скрипт. Бекап будет в домашней директории.
```
./backup.sh
```

#Восстановление из резервного копирования
>Заменить папку db в папке приложения flaskBlog
