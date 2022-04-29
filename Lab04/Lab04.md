# 4 Лабораторная Работа
## Прищепов Александр НПМ-03-21
### Введение:
- Цель работы:
    -  Приобретение практических навыков взаимодействия пользователя с системой по-
средством командной строки.
### Ход Работы:
1. **Мы переходим в домашний каталог и выполняем следующие действия:**
    - Выводим на экран содержимое каталога при помощи команды ls с использование различных опций (таких как -a, -l, -alF) (Рис 1)

    рис 1:

![изображение](https://user-images.githubusercontent.com/104249657/165928296-fa7bf399-98cd-4f34-9f7f-9fa360aa474d.png)

2. **Работаем над созданием и удалением каталогов:**
    - Создаём в домашнем каталоге каталог newdir и в нём подкаталог morefun (рис 2):
    
    рис 2:
    
![изображение](https://user-images.githubusercontent.com/104249657/165928558-ad5f8449-da5e-4d65-96a6-62fa2304c76e.png)

    - В каталоге мы создаём одной командой три каталога (используя команду mkdir и вводя названия каталогов через пробел) и затем удаляем их (Рис 3)
    
    рис 3:
    
![изображение](https://user-images.githubusercontent.com/104249657/165928793-c90aa002-68f4-42b0-904b-702a4891e9eb.png)

    - Пробуем удалить каталог используя команду rm, но замечаем, что это невзоможно без опции -r и удаляем каталог morefun(Рис 4)
    
    рис 4:
    
![изображение](https://user-images.githubusercontent.com/104249657/165928992-35b380fb-89aa-47b3-8c3b-ea49ffa8879d.png)

3. **С помощью команды man находим информацию по команду ls и ищем нужные нам опции:

    - Смотрим нужные нам опции через команду man(Рис 5, 6)

    рис 5:
    
    ![изображение](https://user-images.githubusercontent.com/104249657/165929255-c3bf701a-284b-4401-9f10-2d0c2c98c60c.png)
    
    рис 6:
    
    ![изображение](https://user-images.githubusercontent.com/104249657/165929335-27450992-2851-42b8-8eeb-ef420d0c94fb.png)

    - Находим опции -R (опция для просмотря содержимого каталога и его подкаталогов) и -t (для сортировки содержимого каталога по времени) и выполняем опции (рис 7, 8)

    рис 7:
    
    ![изображение](https://user-images.githubusercontent.com/104249657/165929611-1aac209c-4bd9-4523-8881-ffdb269215ed.png)

    рис 8:
    
    ![изображение](https://user-images.githubusercontent.com/104249657/165929681-c502d3ed-b02f-4dd4-943a-48d848bdb8d3.png)
    
    - Используем команду man для поиска информации для других команд (cd, pwd, mkdir, rmdir, rm.) (рис 9, 10, 11, 12)
    
    рис 9:
    
    ![изображение](https://user-images.githubusercontent.com/104249657/165929849-e5b29377-7fa4-42c1-8e3f-e6737ec946ed.png)
    
    рис 10:
    
    ![изображение](https://user-images.githubusercontent.com/104249657/165929936-ff0b8d23-a700-460c-96f3-7860ce42a8f5.png)

    рис 11:
    
    ![изображение](https://user-images.githubusercontent.com/104249657/165929981-f8962394-dc5b-4cb7-955c-d5b51cea9474.png)

    рис 12:
    
    ![изображение](https://user-images.githubusercontent.com/104249657/165930059-15fa3a90-f6d1-461a-bfe1-30ec0eea04a9.png)
    
4. **Используя информацию, полученную при помощи команды history, выполняю модификацию и исполнение нескольких команд из буфера команд:** (рис 13, 14)
    
    рис 13:
    
    ![изображение](https://user-images.githubusercontent.com/104249657/165930270-2b1d88dd-6feb-47e3-a08b-490d5dee5b1e.png)

    рис 14:
    
    ![изображение](https://user-images.githubusercontent.com/104249657/165930324-ba7f66ec-3426-4bb6-9004-231859e87a82.png)

## Заключение, вывод:
Я Приобрёл практические навыки взаимодействия пользователя с системой посредством командной строки.

### Ответы на Контрольные вопросы:
1. Командная строка(консоль или терминал) - это программа, которая позволяет управлять компьютером путём ввода текстовых команд с клавиатуры 2. Абсолютный путь определяется при помощи команды pwd.
3. Имена и тип файлов в текущем каталоге можно определить при помощи функции ls -f.
4. Скрытые файлы можно отобразить при помощи ls -a.
5. Файлы и каталоги удаляются при помощи функции rm, но для удаления каталога требуется 
опция -r. 
6. Последние выполненные команды можно вывести на экран с помощью команды history 7. Чтобы получить доступ к истории, нужно написать history. Чтобы модифицировать команду, нужно написать: !:s//. 
8. На данной фотографии последовательно выполняются написанные в одной строке команды cd и ls 
9. Экранирование символа - это использование специального символа как обычного.
10. После команды ls -l на экран выводятся файлы и подкаталоги, содержащиеся в текущем, с данными об владельце, содержимом и времени редактирования 
11. Относительный путь - это путь от корневого каталога или от текущего местоположения пользователя. Абсолютный путь - полный путь к файлу, независящий от текущего местоположения 
12. С помощью команды man можно получить информацию о любой команде: man  
13. Нажатие клавишы Tab автоматически дополнит текущую команду или путь к файлу. Двойное нажатие позволяет увидеть варианты дополнения