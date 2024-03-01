# Лабараторная работа №2
## Первый контейнер
### Цель работы
* Данная лабораторная работа знакомит с основами контейнеризации и подготавливает рабочее место для выполнения следующих лабораторных работ.
### Задание
* Установить Docker Desktop и проверить его работоспособность.
## Шаги выполнения
### Папка 
![Снимок экрана 2024-03-01 180610](https://github.com/Iulia1511/containers02/assets/159126852/24c8ce75-fe36-4a48-95ba-31634f60d0a7)


### Клонирование репозитория:
![Снимок экрана 2024-03-01 114523](https://github.com/Iulia1511/containers02/assets/159126852/98109eec-cb22-45df-84cd-c4edbc9cac77)

### Откройте терминал в папке containers02 и выполните команду: docker build -t containers02 
![AS](https://github.com/Iulia1511/containers02/assets/159126852/b3886297-7578-402e-8130-a5670bab815a)
* На создание образа ушло 2.2 секунды.
### Выполните команду для запуска контейнера: docker run --name containers02 containers02
 ![2](https://github.com/Iulia1511/containers02/assets/159126852/3c3a21dc-230a-452b-a945-3446f6667b68)
### Удалите контейнер и запустите снова, выполнив команды: docker rm containers02; docker run -ti --name containers02 containers02 bash
![3](https://github.com/Iulia1511/containers02/assets/159126852/2592ef2b-c599-4909-8165-54ea6339dc40)
### В открывшемся окне выполните команды: cd /var/www/html/; ls -l
![AS](https://github.com/Iulia1511/containers02/assets/159126852/82792aed-e45f-4af0-9c6c-681f3ad844b1)
# Вывод 
### Я ознакомилась с основами контейниризации и подготовила рабочее место для выполнения следующих работ



