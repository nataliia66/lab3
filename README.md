# lab3

***
   РОССИЙСКИЙ УНИВЕРСИТЕТ ДРУЖБЫ НАРОДОВ
===
   Факультет физико-математических и естественных наук
===
   Кафедра прикладной информатики и теории вероятностей
====


ОТЧЕТ 
ПО ЛАБОРАТОРНОЙ РАБОТЕ № 3	
===
*дисциплина:	Архитектура компьютера*



Студент: Нефёдова Наталия                                     


	Группа: НПИбд-02-22                                       



МОСКВА
2022 г.
***


Цель работы
Целью работы является изучить идеологию и применение средств контроля версий. Приобрести практические навыки по работе с системой git.

1.	Начнём с установки Git на Windows и регистрации в GitHub
![first picture](![image](https://user-images.githubusercontent.com/99801100/198848903-69a21379-e06b-4a46-bc06-83134565cf7f.png)

***

2.	Утсановка Git
![second picture](![image](https://user-images.githubusercontent.com/99801100/198848931-8b51839a-26c4-4f11-8f76-3836865a8ed2.png)

3.Проверим установился ли git, для этого через командную строку (чтобы выйти в командную строку введём в поиске cmd.


А далее в командой строке пишем слово git.
![third picture](![image](https://user-images.githubusercontent.com/99801100/198848963-fe1c3103-9a7e-4ad6-9cf6-7d0c4efdee5f.png)

4.
Сначала сделаем предварительную конфигурацию git. Необходимо открыть терминал и 
ввести следующие команды, указав своё имя и email:
•	git config --global user.name "<Name Surname>"
•	git config --global user.email "<work@mail>"
•	Настроим utf-8 в выводе сообщений git:
git config --global core.quotepath false
•	Зададим имя начальной ветки (будем называть её master):
git config --global init.defaultBranch master
•	Параметр autocrlf:
git config --global core.autocrlf input
•	Параметр safecrlf:
git config --global core.safecrlf warn
  
![fifth picture]![image](https://user-images.githubusercontent.com/99801100/198848996-4f5f77ac-e2f9-43ca-84f2-803a1834e004.png)
***
  
5.Для последующей идентификации пользователя на сервере репозиториев
необходимо сгенерировать пару ключей (приватный и открытый):
ssh-keygen -C "Имя Фамилия <work@mail>"

1132226537@pfur.com – work email
  
![6 picture]
  ![image](https://user-images.githubusercontent.com/99801100/198849038-97ec68d8-f74c-4ebc-a1a2-7a6a22bf5083.png)
***
6.	Создание SSH ключа
![7 picture](https://user-images.githubusercontent.com/99801100/198849384-d4f79c55-b2b1-4257-9759-f4275bd9b9be.png)
 Теперь у меня есть публичный и приватный ключи, которые я могу использовать для входа на серверы. 
  7.Введём ключ в GitHub
  ![image](https://user-images.githubusercontent.com/99801100/198849427-f131470b-1bd9-49c5-8a02-cc4cc4b2e5b1.png)
![image](https://user-images.githubusercontent.com/99801100/198849432-f61465d2-bf54-4f9e-826e-bc372140c19e.png)

  8. Создадим каталог
  ![image](https://user-images.githubusercontent.com/99801100/198849448-1bd35a60-8f6e-4cd4-b3fa-408bdfa8528e.png)

  9.Сознание рабочего пространства и репозитория курса на основе шаблона 
  
  При выполнении лабораторных работ следует придерживаться структуры рабочего пространства. Рабочее пространство по предмету располагается в следующей иерархии:
![image](https://user-images.githubusercontent.com/99801100/198849475-583044f3-c5ad-43d9-9651-7acf09c0e1d6.png)
10.	Репозиторий на основе шаблона можно создать через web-интерфейс github. 
  
  Перейдите на станицу репозитория с шаблоном курса [https://github.com/yam adharma/course-directory-student-template]




  
  
  
  
   




