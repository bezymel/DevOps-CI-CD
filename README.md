# Домашнее задание к занятию "Что такое DevOps? CI/CD" - `Немцев Денис`


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

### Задание 1

Что нужно сделать:

1. Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.
2. Установите на машину с jenkins golang.
3. Используя свой аккаунт на GitHub, сделайте себе форк репозитория. В этом же репозитории находится дополнительный материал для выполнения ДЗ.
4. Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build ..
   
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

### Ответ 1
![image](https://github.com/bezymel/DevOps-CI-CD/assets/129361495/669202cc-a8ea-4494-8318-361f90db9376)
![image](https://github.com/bezymel/DevOps-CI-CD/assets/129361495/d34983fe-795e-4152-a229-0c603bcd9518)
![image](https://github.com/bezymel/DevOps-CI-CD/assets/129361495/3f2fda8e-c54c-467c-bf3b-6678395276fb)
![image](https://github.com/bezymel/DevOps-CI-CD/assets/129361495/4c3e3e78-6611-4573-b780-395f6d232bcb)
![image](https://github.com/bezymel/DevOps-CI-CD/assets/129361495/221ea715-a6b0-4197-a683-6564689d24f3)




### Задание 2

Что нужно сделать:

1. Создайте новый проект pipeline.
2. Перепишите сборку из задания 1 на declarative в виде кода.
   
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

### Ответ 2


### Задание 3

Что нужно сделать:

1. Установите на машину Nexus.
2. Создайте raw-hosted репозиторий.
3. Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
4. Загрузите файл в репозиторий с помощью jenkins.
   
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

### Ответ 3

