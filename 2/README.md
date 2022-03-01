# Домашнее задание к занятию "Основы работы в MasterScada. Настройка OPC"

### Цель задания

В результате выполнения этого задания вы научитесь настраисать OPC сервер, обен данными по протоколу MODBUS и поработаете с типами данных в MasterOPC. Так же Вы научитесь настраивать связь между OPC сервером и проектом в MasterSCADA.

1. Изучить настройки OPC серверов
2. Изучить методы настройки обена данными по MODBUS протоколу
3. Определять формат взаимодействия с тегами чтение/запись
4. Научиться создавать проект в MasterSCADA
5. Научиться подклюать OPC сервек к проекту MasterSCADA

------

### Чеклист готовности к домашнему заданию

1. Доступ к сети Интернет
2. Наличие личного Google диска

------

### Инструкция к заданию

1. Установить Эмулятор ПЛК - Modbus Slave
2. Открыть в Modbus Slave проекты эмуляции ПЛК - 4шт. - https://drive.google.com/drive/folders/1q-BVFVM1eT6_NsB5KSiX9MAwaZ9A6gwu?usp=sharing по инструкции - https://docs.google.com/presentation/d/1LjhkA1mcjsYDAgIH2K_uvA63RiSjkBeZ1YNeUqPLlLU/edit?usp=sharing
3. Установить Master OPC - https://drive.google.com/file/d/1LLmRXtbd7RHQIFwsJLbtNKbqHpk1gFDM/view?usp=sharing
4. В MasterOPC настроить OPC UA сервер и настроить связь со всеми тегами из Modbus Slave
5. Для проверки домашнего задания преподавателем отправьте ссылку на ваш проект OPC сервера в личном кабинете
6. Любые вопросы по решению задач задавайте в чате учебной группы.

------

### Инструменты/ дополнительные материалы, которые пригодятся для выполнения задания

1. Эмулятор ПЛК - Modbus Slave https://www.modbustools.com/download.html согласно инструкции https://docs.google.com/document/d/1kiTtyQV1EHN5S_Hopq9sAZ8zu2fNbfmPZXmVdzWcDSc/edit?usp=sharing
2. Master OPC - https://insat.ru/products/?category=1666 согласно инструкции https://docs.google.com/document/d/1CZCTgLDDiIoJ71bQmw-qN8bb7EhrhPHLaTMso9bEOaA/edit?usp=sharing
3. MasterSCADA 4D - https://masterscada.ru/download4 согласно инструкции https://docs.google.com/document/d/1ouPhPmJ9GnwnXnG1YbKZQMoK7ppOYN9FYDVb4Oh8kGs/edit?usp=sharing
4. Установить MasterSCADA 4D - https://drive.google.com/file/d/1f9MKYU7BrWC4ZQ_WjnVfPxZYkgcZVf81/view?usp=sharing
5. Создать новый проект в MasterSCADA 4D

------

### Задание 1
1. В MasterOPC создать OPC сервер с доступом по OPC UA и подключить все теги из проектов Master Slave.
2. Запустить MasterOPC в режиме исполнения и проверить обмен данными с MasterSlave (8-DI, 8-DO, 8-AI и 8-AO тегов)

------

### Задание 2

1. Создать новый проект в MasterSCADA 4D
2. Настроить связь с OPC UA сервером созданном в Master OPC
3. Загрузить все теги из OPC сервера в проект MasterSCADA
4. Поверить обмен данными в режиме исполнения MasterSCADA (Master Slave - MasterOPC - MasterSCADA)

------

### Правила приема работы

1. Отправлена ссылка на проекты MasterOPC и MasterSCADA (Google Doc) с выполненным заданием в личном кабинете.
2. Проекты MasterOPC и MasterSCADA на личном Google Disk
3. К проектам MasterOPC и MasterSCADA настроены права доступа “Просматривать могут все в Интернете, у кого есть ссылка".

------

### Критерии оценки

1. В MasterOPC создан OPC UA сервер
2. В режиме имполнения MasterOPC отражаются изменения всех тегов из эмулятора ПЛК Modbus Slave согласно типу данных и режиму чтение/запись
3. В MasterSCAD 4D создан проект
4. В проекте MasterSCADA 4D настроена связь с OPC UA MasterOPC
5. В проекте MasterSCADA 4D загружены все теги из OPC сервера MasterOPC
6. В режиме исполнения проекта MasterSCADA 4D (при запущенном режиме исполнения MasterOPC) оражаются изменение все тегов в эмуляторе ПЛК Mosdbus Slave согластно типу данных. 
