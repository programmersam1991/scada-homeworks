# Домашнее задание к занятию "Основы работы в MasterScada. Настройка OPC"

### Цель задания

В результате выполнения этого задания вы научитесь настраивать OPC-сервер, обмен данными по протоколу Modbus и поработаете с типами данных в MasterOPC. Также вы научитесь настраивать связь между OPC-сервером и проектом в MasterSCADA.

1. Изучить настройки OPC-серверов
2. Изучить методы настройки обмена данными по Modbus протоколу
3. Определять формат взаимодействия с тегами чтение/запись
4. Научиться создавать проект в MasterSCADA
5. Научиться подключать OPC-сервер к проекту MasterSCADA

------

### Чеклист готовности к домашнему заданию

1. Доступ к сети Интернет
2. Наличие личного Google Диска

------

### Инструкция к заданию

1. Установить Эмулятор ПЛК - Modbus Slave https://www.modbustools.com/download.html согласно инструкции https://docs.google.com/document/d/1kiTtyQV1EHN5S_Hopq9sAZ8zu2fNbfmPZXmVdzWcDSc/edit?usp=sharing
2. Открыть в Modbus Slave проекты эмуляции ПЛК - 4шт. - https://drive.google.com/drive/folders/1OXjO8pzdHCP9vEJVN65R6EN0GAurRmCg?usp=sharing по инструкции - https://docs.google.com/presentation/d/1LjhkA1mcjsYDAgIH2K_uvA63RiSjkBeZ1YNeUqPLlLU/edit?usp=sharing
3. Установить MasterOPC - https://insat.ru/products/?category=1666 согласно инструкции https://docs.google.com/document/d/1CZCTgLDDiIoJ71bQmw-qN8bb7EhrhPHLaTMso9bEOaA/edit?usp=sharing
4. MasterSCADA 4D - https://masterscada.ru/download4 согласно инструкции https://docs.google.com/document/d/1ouPhPmJ9GnwnXnG1YbKZQMoK7ppOYN9FYDVb4Oh8kGs/edit?usp=sharing
5. Выполнить задания 1 и 2
6. Для проверки домашнего задания преподавателем отправьте ссылку на ваш проект OPC-сервера в личном кабинете
7. Любые вопросы по решению задач задавайте в чате учебной группы.

------

### Инструменты/ дополнительные материалы, которые пригодятся для выполнения задания

1. Google drive
2. Эмулятор ПЛК - Modbus Slave 
3. Master OPC
4. MasterSCADA 4D 

------

### Задание 1
1. В MasterOPC создать OPC-сервер с доступом по OPC UA и подключить все теги из проектов Master Slave.
2. Запустить MasterOPC в режиме исполнения и проверить обмен данными с MasterSlave (8-DI, 8-DO, 8-AI и 8-AO тегов)

------

### Задание 2

1. Создать новый проект в MasterSCADA 4D
2. Настроить связь с OPC UA-сервером, созданном в Master OPC
3. Загрузить все теги из OPC-сервера в проект MasterSCADA
4. Поверить обмен данными в режиме исполнения MasterSCADA (Master Slave - MasterOPC - MasterSCADA)

------

### Правила приема работы

1. Файлы проектов MasterOPC и MasterSCADA размещены на личном Google Диске.
2. К файлам проектов MasterOPC и MasterSCADA на Google Диске настроены права доступа “Просматривать могут все в Интернете, у кого есть ссылка".
3. Отправлена ссылка на проекты MasterOPC и MasterSCADA (Google Диск) с выполненным заданием в личном кабинете.

------

### Критерии оценки

1. В MasterOPC создан OPC UA-сервер.
2. В режиме имполнения MasterOPC отражаются изменения всех тегов из эмулятора ПЛК Modbus Slave согласно типу данных и режиму чтение/запись.
3. В MasterSCADA 4D создан проект.
4. В проекте MasterSCADA 4D настроена связь с OPC UA MasterOPC.
5. В проекте MasterSCADA 4D загружены все теги из OPC сервера MasterOPC.
6. В режиме исполнения проекта MasterSCADA 4D (при запущенном режиме исполнения MasterOPC) отражаются изменения всех тегов в эмуляторе ПЛК Mosdbus Slave согласно типу данных. 
