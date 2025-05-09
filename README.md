# Что такое DevOps. СI/СD (8-02)
## Щербатых Антон

### Задание 1
1. Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.

   ![alt text](https://github.com/Anton-Shcherbatykh/FOPS32-3/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%201_1.jpg)
   
2. Установите на машину с jenkins golang.
   ![alt text](https://github.com/Anton-Shcherbatykh/FOPS32-3/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%201_2.jpg)
   
3. Используя свой аккаунт на GitHub, сделайте себе форк репозитория (https://github.com/netology-code/sdvps-materials.git). В этом же репозитории находится дополнительный материал для выполнения ДЗ.
    ![alt text](https://github.com/Anton-Shcherbatykh/FOPS32-3/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%201_3.jpg)
   
4. Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build ..
   ![alt text](https://github.com/Anton-Shcherbatykh/FOPS32-3/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%201_4_3.jpg)
   ![alt text](https://github.com/Anton-Shcherbatykh/FOPS32-3/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%201_4_1.jpg)
   ![alt text](https://github.com/Anton-Shcherbatykh/FOPS32-3/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%201_4_2.jpg)


### Задание 2
1. Создайте новый проект pipeline.
2. Перепишите сборку из задания 1 на declarative в виде кода.
   ![alt text](https://github.com/Anton-Shcherbatykh/FOPS32-3/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_2_3.jpg)
   ![alt text](https://github.com/Anton-Shcherbatykh/FOPS32-3/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_2_1.jpg)
   ![alt text](https://github.com/Anton-Shcherbatykh/FOPS32-3/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_2_2.jpg)
   
### Задание 3
1. Установите на машину Nexus.

   ![alt text](https://github.com/Anton-Shcherbatykh/FOPS32-3/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_3_1.jpg)
   ![alt text](https://github.com/Anton-Shcherbatykh/FOPS32-3/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_3_1_1.jpg)
      
2. Создайте raw-hosted репозиторий.
   
   ![alt text](https://github.com/Anton-Shcherbatykh/FOPS32-3/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_3_2.jpg)
   
3. Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.

   ![alt text](https://github.com/Anton-Shcherbatykh/FOPS32-3/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_3_3.jpg)
     
4. Загрузите файл в репозиторий с помощью jenkins.
 ![alt text](https://github.com/Anton-Shcherbatykh/FOPS32-3/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_4_1.jpg)
 ![alt text](https://github.com/Anton-Shcherbatykh/FOPS32-3/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_4_2.jpg)
 ![alt text](https://github.com/Anton-Shcherbatykh/FOPS32-3/blob/main/images/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5_4_3.jpg)











### Дополнительные материалы для выполнения домашних заданий из блока "Введение в DevOps"


- [Дополнительный материал для занятия "8.2. Что такое DevOps. СI/СD"](CICD/8.2-hw.md)

- [Дополнительный материал для занятия "8.3. GitLab"](https://github.com/netology-code/sdvps-materials/tree/main/gitlab)
