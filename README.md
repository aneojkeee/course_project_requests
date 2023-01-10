# Учебный проект на тему: "Основы языка программирования Python".(Educational project on the topic: "Fundamentals of the Python programming language")

Возможна такая ситуация, что мы хотим показать друзьям фотографии из социальных сетей, но соц. сети могут быть недоступны по каким-либо причинам. Давайте защитимся от такого.
Нужно написать программу для резервного копирования фотографий с профиля(аватарок) пользователя "VK" в облачное хранилище Яндекс.Диск.
Для названий фотографий использовать количество лайков, если количество лайков одинаково, то добавить дату загрузки.
Информацию по сохраненным фотографиям сохранить в json-файл.

It is possible that we want to show friends photos from social networks, but the social. networks may be unavailable for any reason. Let's protect ourselves from this. You need to write a program for backing up photos from the profile (avatars) of a "VK" user to the Yandex.Disk cloud storage. For photo titles, use the number of likes, if the number of likes is the same, then add the upload date. Save information on saved photos to a json file.

## Задачи проекта:
1. Получать фотографии из профиля. 
2. Сохранять фотографии максимального размера(ширина/высота в пикселях) на Я.Диске.
3. Для имени фотографий использовать количество лайков. 
4. Сохранять информацию по фотографиям в json-файл с результатами. 

## Project objectives:
1. Get profile photos.
2. Save photos of the maximum size (width/height in pixels) on Yandex.Disk.
3. Use the number of likes for the photo name.
4. Save information on photos to a json file with results.

### Требования:

* `pip install -r requirements.txt`
* получить на выходе json-файл

### Requirements:
* `pip install -r requirements.txt`
* get json file

### Пример json-файла (json file example):

```  
    [{  
    "file_name": "34.jpg",  
    "size": "z"  
    }]
