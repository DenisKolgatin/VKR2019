# VKR2019
Тема ВКР: Электронное обучение школьников

Объект исследований: современные образовательные системы и методы, применимые для обучения прикладным навыкам.

Предмет исследований: образовательные платформы, размещенные в сети "Интернет".

Процессы верхнего уровня:

А1 Регистрация (относится к внешней среде; обеспечивает идентификацию пользователя и занесение его данных в базу данных)

А2 Освоение лекционных материалов (относится к внутренней среде; Получение учеником теоретических знаний, необходимых для данного уровня;)

А3 Закрепление знаний на тренажере (относится к внутренней среде; Позволяет ученику проверить и закрепить свои знания)

А4 Завершение обучения на уровне и обновление статистики (относится к внутренней среде; Завершение процесса обучения для данного урока и обновление статистики пользователя)

А4 Анализ информации (относится к внутренней среде; поддерживается базой данных PACS-системы)

А5 Выдача аналитики (относится к внешней среде; обеспечивает получение аналитики; поддерживается внешней PACS-системой)

Цель моделирования: определение автоматизируемых функций

Точка зрения - директор учебного центра

### Лабораторная работа 4
Декомпозиция автоматизируемых блоков до уровня, прямо сопоставляемого с программными модулями

Ветка А0:
![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/A02.png)

Ветка А1-А4:
![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/A1-3.png)

Ветка А11-А13:
![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/%D0%B011.png)

Ветка А21-А23:
![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/%D0%B021-23.png)

Ветка А31-А33:
![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/A3133(2).png)

Ветка А41-А43:
![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/%D0%A1%D0%B5%D1%80%D1%82%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%82.png)

### Лабораторная работа 5
 DFD диаграммы курсового проекта
1. Определение основных средств автоматизации:
Определение конфигурации технических средств (рабочие станции, серверы, другое оборудование) - Рабочие станции (ПК), сервер.

Определение конфигурации программных средств (одноуровневые, многоуровневые, встроенные, распределенные) - Многоуровневая.

Определение допустимых видов хранилищ и их размещения - БД.

2. Разработка диаграмм в RAMUS
Декомпозиция всех автоматизируемых блоков в DFD 

#Декомпозиция блока A31(генерация задания): 
![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/%D0%B031dfd.png)

#Декомпозиция блока A32(Выполнение задания): 
![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/%D0%B032dfd.png)

#Декомпозиция блока A33(Проверка и интеллектуальный анализ выполнения): 
![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/%D0%B033dfd.png)

Построение ![ERD](https://github.com/DenisKolgatin/SkladForCurs/blob/master/%D0%A0%D0%BE%D0%BB%D0%B8%D0%A2%D0%B5%D0%BA%D1%81%D1%82)  для всех ролей:

![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/%D0%A0%D0%BE%D0%BB%D0%B8.png)

Построение ![ERD](https://github.com/DenisKolgatin/SkladForCurs/blob/master/%D0%9F%D0%BE%D1%82%D0%BE%D0%BA%D0%B8%D0%A2%D0%B5%D0%BA%D1%81%D1%82) для всех потоков:

![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/%D0%BF%D0%BE%D1%82%D0%BE%D0%BA%D0%B8.png)

Построение ![ERD](https://github.com/DenisKolgatin/SkladForCurs/blob/master/%D0%9C%D0%BE%D0%B4%D1%83%D0%BB%D0%B8) для всех модулей:

![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/jLNDgjD055xVUOhXxkyRkBZMXt0Tas13aqOcAIvKw8zKeGj513TIKDmAwKziIDhq5SuyYQ_WbqdQnDZQeN0fbEPyFz_CoJdqFWWD4Guyb_tEzYpeEVqNXZ0yRhf64F1NxAPZcBtdmX_qhIU-wml-jEk4DhjvB8J_ignqN510z8LbYsRf3IjTw2lbj9OJoYYfIhVqar8vf8Xs-4Jo0vTlAKTXIz7j.png)

