# Задачи
## Часть 1. Создание сети и проверка настроек коммутатора по умолчанию
### Шаг 1.
![image](https://user-images.githubusercontent.com/22404268/190704703-a2d2a61a-8216-4f72-8ddc-fc00ff116c6b.png)
Почему нужно использовать консольное подключение для первоначальной настройки коммутатора? Почему нельзя подключиться к коммутатору через Telnet или SSH? - Устройство из коробки мб не настроено
### Шаг 2.
![image](https://user-images.githubusercontent.com/22404268/190705079-dafcb128-b114-4028-9730-9be4cebe620e.png)
![image](https://user-images.githubusercontent.com/22404268/190705129-fe76d037-0dce-4996-9a3b-5bd8e3b179c0.png)

Почему нужно использовать консольное подключение для первоначальной настройки коммутатора? Почему нельзя подключиться к коммутатору через Telnet или SSH? - *Устройство из коробки пустое?*  
  Сколько интерфейсов FastEthernet имеется на коммутаторе 2960? - 24  
  Сколько интерфейсов Gigabit Ethernet имеется на коммутаторе 2960? - 2  
  Каков диапазон значений, отображаемых в vty-линиях? - 0 4/ 5 15  
  Почему появляется это сообщение? startup-config is not present - нет загрузочной конфигурации  
  Назначен ли IP-адрес сети VLAN 1? - нет  
  Какой MAC-адрес имеет SVI? - 0001.439b.6774  
  Данный интерфейс включен? - выключен  
  Какие выходные данные вы видите?  
  ![image](https://user-images.githubusercontent.com/22404268/190705567-7a96064c-4619-4da1-a566-752c359ef4e1.png)
  ![image](https://user-images.githubusercontent.com/22404268/190705918-2a7c7e83-0e3e-4121-8387-c126aa25c9c0.png)
  ![image](https://user-images.githubusercontent.com/22404268/190706251-6a56bfca-14a7-43fa-b466-ae45213eda3a.png)
  ![image](https://user-images.githubusercontent.com/22404268/190706334-5d037098-b4e9-4b3f-91fa-03f6f0949202.png)
  ![image](https://user-images.githubusercontent.com/22404268/190706496-59f1a7fd-6d92-4679-a06b-f10648116942.png)
## Часть 2. Создание сети и настройка основных параметров устройства
### Шаг 1.
  ![image](https://user-images.githubusercontent.com/22404268/190707587-e6618f39-e8db-4523-89cd-a2724b2baee7.png)
  ![image](https://user-images.githubusercontent.com/22404268/190707707-86749efc-3163-4b82-a6a9-73a1a44ec2ca.png)
  ![image](https://user-images.githubusercontent.com/22404268/190707831-dd35672e-125b-480e-a87b-3cf24c73b536.png)
  ![image](https://user-images.githubusercontent.com/22404268/190708113-23ae42dc-ceb5-47b8-a8e0-be5838bc5a93.png)
  Для чего нужна команда login? - как замок, чтобы можно было ввести пароль
### Шаг 2.
  ![image](https://user-images.githubusercontent.com/22404268/190708540-76e0dec5-23bc-4d77-9195-e96862a053b2.png)
## Часть 3. Проверка сетевых подключений
### Шаг 1.
![image](https://user-images.githubusercontent.com/22404268/190708908-e9502d8e-f9b6-4e25-8e9a-0a90f2e3dffc.png)
![image](https://user-images.githubusercontent.com/22404268/190709513-b0d0ae92-3a82-4366-ab77-bfa4e38d94a3.png)
![image](https://user-images.githubusercontent.com/22404268/190709644-080c41a6-dff3-49c3-850b-e7eaedbea901.png)
### Шаг 2.
![image](https://user-images.githubusercontent.com/22404268/190710033-f5790ef7-28d2-46ff-81c0-553f6ad7e508.png)
![image](https://user-images.githubusercontent.com/22404268/190710075-afe06bd8-9a8b-4f9d-a9e9-c76b4efe9dd7.png)
![image](https://user-images.githubusercontent.com/22404268/190710718-569ca76c-9eb3-449d-b8d0-f75bf071466f.png)

1.	Зачем необходимо настраивать пароль VTY для коммутатора? - иначе не сможем подключаться удаленно
2.	Что нужно сделать, чтобы пароли не отправлялись в незашифрованном виде? - использовать  secret
