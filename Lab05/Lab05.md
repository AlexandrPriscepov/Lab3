# 2 Лабораторная Работа
## Прищепов Александр НПМ-03-21
### Введение:
- Цель работы:
    -Ознакомление с файловой системой Linux, её структурой, именами и содержанием
каталогов. Приобретение практических навыков по применению команд для работы
с файлами и каталогами, по управлению процессами (и работами), по проверке исполь-
зования диска и обслуживанию файловой системы.
### Ход Работы:
1) Мы выполняем все примеры из первого пункта лабораторной работы (рис 1,2):
    
    рис 1:
    
    ![Снимок экрана от 2022-05-05 14-47-56](https://user-images.githubusercontent.com/104249657/166917078-aab30836-1983-431c-990a-69ae46658e3c.png)
    
    рис 2: (итог)
    
    ![Снимок экрана от 2022-05-05 14-49-21](https://user-images.githubusercontent.com/104249657/166917224-755da3eb-47f0-4240-8bdf-3b90e67003f9.png)
2) Выполняем все команды из второго пункта лабораторной работы, а именно из рисунка 3:
    
    рис 3:
    
    ![Zha1PpNT4IihNgq-iWLIcJ3RFpY4e9yBRpdEe16BqnNT1S7WvqNz6IY2z4picTe6_3dzZbFu1W1nv8IZrIp8WrFl](https://user-images.githubusercontent.com/104249657/166917610-2d9ef468-cd65-491c-bbea-64945c6e7f70.jpg)
    
    фиксируем выполнение: (рис 4,5,6)
    
    рис 4:
    
    ![Снимок экрана от 2022-05-05 14-53-01](https://user-images.githubusercontent.com/104249657/166917776-274415f4-9bc5-4cf3-8e43-daa6c004eaa7.png)
    
    рис 5:
    
    ![Снимок экрана от 2022-05-05 14-54-11](https://user-images.githubusercontent.com/104249657/166917918-8cded9ef-45df-4913-967d-60bb162cc5a7.png)
    
    рис 6:
    
    
    ![Снимок экрана от 2022-05-05 14-55-04](https://user-images.githubusercontent.com/104249657/166918101-78354ec3-f567-4444-9825-536b260ab490.png)
    
    получаем результат: (рис 7)
    
    рис 7:
    
    ![Снимок экрана от 2022-05-05 14-56-30](https://user-images.githubusercontent.com/104249657/166918255-4cb33d54-c8e0-4f17-b007-d119193551e4.png)

3) Определяем опции команды chmod (рис 8,9)

    рис 8:
    
    ![Снимок экрана от 2022-05-05 14-58-03](https://user-images.githubusercontent.com/104249657/166918534-b53d9c2c-c145-46c8-bc01-f0e514c191bf.png)
    
    рис 9:
    
    ![Снимок экрана от 2022-05-05 14-58-51](https://user-images.githubusercontent.com/104249657/166918615-b5f7b33f-eb52-4202-bb12-d120379d02bf.png)

4)  Проделывем приведённые упражнения, записывая в отчёт по лабораторной работе используемые при этом команды (рис 10)

    рис 10:
    
    ![Снимок экрана от 2022-05-05 15-00-36](https://user-images.githubusercontent.com/104249657/166918874-8e8d357c-054d-47cb-b1ee-4d4c29c8c78d.png)

5)  Прочитываем man по командам mount, fsck, mkfs, kill (рис 11):

    рис 11:
    
    ![Снимок экрана от 2022-05-05 15-01-25](https://user-images.githubusercontent.com/104249657/166919039-c0451c1d-7d03-4346-be4c-21ca20f66af5.png)

   ## Вывод:
   Я ознакомился с файловой системой Linux, её структурой, именами и содержанием
каталогов. Я приобрёл практические навыки по применению команд для работы
с файлами и каталогами, по управлению процессами (и работами), по проверке исполь-
зования диска и обслуживанию файловой системы.

   ## Ответы на контрольные вопросы:
   1.Ext2, Ext3, Ext4 или Extended Filesystem - это стандартная файловая система для Linux. Она была разработана еще для Minix. Она самая стабильная из всех существующих, кодовая база изменяется очень редко и эта файловая система содержит больше всего функций. Версия ext2 была разработана уже именно для Linux и получила много улучшений. В 2001 году вышла ext3, которая добавила еще больше стабильности благодаря использованию журналирования. В 2006 была выпущена версия ext4, которая используется во всех дистрибутивах Linux до сегодняшнего дня. В ней было внесено много улучшений, в том числе увеличен максимальный размер раздела до одного экзабайта.

    JFS или Journaled File System была разработана в IBM для AIX UNIX и использовалась в качестве альтернативы для файловых систем ext. Сейчас она используется там, где необходима высокая стабильность и минимальное потребление ресурсов. При разработке файловой системы ставилась цель создать максимально эффективную файловую систему для многопроцессорных компьютеров. Также как и ext, это журналируемая файловая система, но в журнале хранятся только метаданные, что может привести к использованию старых версий файлов после сбоев.

    ReiserFS - была разработана намного позже, в качестве альтернативы ext3 с улучшенной производительностью и расширенными возможностями. Она была разработана под руководством Ганса Райзера и поддерживает только Linux. Из особенностей можно отметить динамический размер блока, что позволяет упаковывать несколько небольших файлов в один блок, что предотвращает фрагментацию и улучшает работу с небольшими файлами. Еще одно преимущество - в возможности изменять размеры разделов на лету. Но минус в некоторой нестабильности и риске потери данных при отключении энергии. Раньше ReiserFS применялась по умолчанию в SUSE Linux, но сейчас разработчики перешли на Btrfs.

    XFS - это высокопроизводительная файловая система, разработанная в Silicon Graphics для собственной операционной системы еще в 2001 году. Она изначально была рассчитана на файлы большого размера, и поддерживала диски до 2 Терабайт. Из преимуществ файловой системы можно отметить высокую скорость работы с большими файлами, отложенное выделение места, увеличение разделов на лету и незначительный размер служебной информации.

    XFS - журналируемая файловая система, однако в отличие от ext, в журнал записываются только изменения метаданных. Она используется по умолчанию в дистрибутивах на основе Red Hat. Из недостатков - это невозможность уменьшения размера, сложность восстановления данных и риск потери файлов при записи, если будет неожиданное отключение питания, поскольку большинство данных находится в памяти.

    Btrfs или B-Tree File System - это совершенно новая файловая система, которая сосредоточена на отказоустойчивости, легкости администрирования и восстановления данных. Файловая система объединяет в себе очень много новых интересных возможностей, таких как размещение на нескольких разделах, поддержка подтомов, изменение размера не лету, создание мгновенных снимков, а также высокая производительность. Но многими пользователями файловая система Btrfs считается нестабильной. Тем не менее, она уже используется как файловая система по умолчанию в OpenSUSE и SUSE Linux.
    2./ — root каталог. Содержит в себе всю иерархию системы;

/bin — здесь находятся двоичные исполняемые файлы. Основные общие команды, хранящиеся отдельно от других программ в системе (прим.: pwd, ls, cat, ps);

/boot — тут расположены файлы, используемые для загрузки системы (образ initrd, ядро vmlinuz);

/dev — в данной директории располагаются файлы устройств (драйверов). С помощью этих файлов можно взаимодействовать с устройствами. К примеру, если это жесткий диск, можно подключить его к файловой системе. В файл принтера же можно написать напрямую и отправить задание на печать;

/etc — в этой директории находятся файлы конфигураций программ. Эти файлы позволяют настраивать системы, сервисы, скрипты системных демонов;

/home — каталог, аналогичный каталогу Users в Windows. Содержит домашние каталоги учетных записей пользователей (кроме root). При создании нового пользователя здесь создается одноименный каталог с аналогичным именем и хранит личные файлы этого пользователя;

/lib — содержит системные библиотеки, с которыми работают программы и модули ядра;

/lost+found — содержит файлы, восстановленные после сбоя работы системы. Система проведет проверку после сбоя и найденные файлы можно будет посмотреть в данном каталоге;

/media — точка монтирования внешних носителей. Например, когда вы вставляете диск в дисковод, он будет автоматически смонтирован в директорию /media/cdrom;

/mnt — точка временного монтирования. Файловые системы подключаемых устройств обычно монтируются в этот каталог для временного использования;

/opt — тут расположены дополнительные (необязательные) приложения. Такие программы обычно не подчиняются принятой иерархии и хранят свои файлы в одном подкаталоге (бинарные, библиотеки, конфигурации);

/proc — содержит файлы, хранящие информацию о запущенных процессах и о состоянии ядра ОС;

/root — директория, которая содержит файлы и личные настройки суперпользователя;

/run — содержит файлы состояния приложений. Например, PID-файлы или UNIX-сокеты;

/sbin — аналогично /bin содержит бинарные файлы. Утилиты нужны для настройки и администрирования системы суперпользователем;

/srv — содержит файлы сервисов, предоставляемых сервером (прим. FTP или Apache HTTP);

/sys — содержит данные непосредственно о системе. Тут можно узнать информацию о ядре, драйверах и устройствах;

/tmp — содержит временные файлы. Данные файлы доступны всем пользователям на чтение и запись. Стоит отметить, что данный каталог очищается при перезагрузке;

/usr — содержит пользовательские приложения и утилиты второго уровня, используемые пользователями, а не системой. Содержимое доступно только для чтения (кроме root). Каталог имеет вторичную иерархию и похож на корневой;

/var — содержит переменные файлы. Имеет подкаталоги, отвечающие за отдельные переменные. Например, логи будут храниться в /var/log, кэш в /var/cache, очереди заданий в /var/spool/ и так далее.
3.Монтирование тома.
4.Отсутствие синхронизации между образом файловой системы в памяти и ее данными на диске в случае аварийного останова может привести к появлению следующих ошибок:

  1. Один блок адресуется несколькими mode (принадлежит нескольким файлам).

  2. Блок помечен как свободный, но в то же время занят (на него ссылается onode).

  3. Блок помечен как занятый, но в то же время свободен (ни один inode на него не ссылается).
  
  4. Неправильное число ссылок в inode (недостаток или избыток ссылающихся записей в каталогах).

  5. Несовпадение между размером файла и суммарным размером адресуемых inode блоков.

  6. Недопустимые адресуемые блоки (например, расположенные за пределами файловой системы).

  7. "Потерянные" файлы (правильные inode, на которые не ссылаются записи каталогов).

  8. Недопустимые или неразмещенные номера inode в записях каталогов.

5.Как создаётся файловая система?

mkfs - позволяет создать файловую систему Linux.

6.Дайте характеристику командам для просмотра текстовых файлов.

Cat - выводит содержимое файла на стандартное устройство вывода

7.Приведите основные возможности команды cp в Linux.

Cp – копирует или перемещает директорию, файлы.

8.Приведите основные возможности команды mv в Linux.

Mv - переименовать или переместить файл или директорию

9.Что такое права доступа? Как они могут быть изменены?

Права доступа к файлу или каталогу можно изменить, воспользовавшись командой chmod. Сделать это может владелец файла (или каталога) или пользователь с правами администратора.