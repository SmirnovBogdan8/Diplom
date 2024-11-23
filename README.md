# Содержание

## ВВЕДЕНИЕ
 
### 1. Совершенствование методик разработки политик, регламентов и инструкций для обеспечения защиты сетей в условиях автоматизации процессов и применения результатов риск-анализа
#### 1.1. Совершенствование подходов к разработке частных политик  
#### 1.2. Совершенствование подходов к разработке частных регламентов 
#### 1.3. Совершенствование подходов к разработке частных инструкций  

### 2. Разработка алгоритма автоматизации процесса формирования политик, регламентов и инструкций с учетом трехуровневой иерархии документов и результатов риск-анализа современных кибератак  
#### 2.1. Проектирование алгоритма автоматизированной разработки частных политик
#### 2.2. Проектирование алгоритма автоматизированной разработки частных регламентов 
#### 2.3. Проектирование алгоритма автоматизированной разработки частных инструкций  

### 3. Программная реализация алгоритма автоматизации для формирования документации, обеспечивающей организационно-правовую защиту сетей с учетом результатов риск-анализа кибератак
#### 3.1. Реализация автоматизированной генерации частных политик 
#### 3.2. Реализация автоматизированной генерации частных регламентов  
#### 3.3. Реализация автоматизированной генерации частных инструкций  

## ЗАКЛЮЧЕНИЕ

## СПИСОК ЛИТЕРАТУРЫ

---
# Задачи исследования

1) Модернизация методик выработки политик, регламентов и инструкций защиты сетей в контексте автоматизации процессов и использования результатов рис-канализа.
2) Разработка алгоритма автоматизации процесса выработки политик, ре-гламентов и инструкций на основе трехуровневой иерархической модели документов с учетом результатов риск-анализа актуальных кибератак.
3) Разработка программной реализации алгоритма, позволяющей автомати-зировать создание пакета документов для обеспечения организационно-правовой за-щиты сетей в контексте рисканализа кибератак.
---
# Описание старых схем

## 1. Входные данные

Пусть защищаемая система (сеть) состоит из множества её технологических компонент. Такой подход существенно облегчает анализ систем, особенно сложных. В этом случае декомпозиция на технологические компоненты (далее – ТК) позволяет глубже вникнуть в существо процессов реализации атак и защиты. В свою очередь, класс атак, реализуемых в отношении защищаемой системы, также может быть разложен на векторы (сценарии) атак, что составляет таблицу "База VA" с атрибутами: Идентификатор вектора атаки, Название вектора атаки. Аналогично для уязвимостей, используемых злоумышленниками, можно записать следующую таблицу "База VB" с атрибутами: Идентификатор уязвимости, Название Уязвимости. Пересечение таких множеств составляет таблица "Наиболее опасные сочетания сценариев и уязвимостей атаки" с атрибутами: Идентификатор вектора атаки, Наименование вектора атаки, Идентификатор уязвимости, Наименование вектора уязвимости.

## 2. Частная политика

Для того, чтобы разработать план мероприятий по обеспечению безопасности Организации в части противодействия сетевой атаки типа необходимо учесть объекты защиты для выделенных сценариев атаки (таблица "Объекты защиты" с атрибутами: Идентификатор объекта защиты, Сценарий атаки, Объект защиты).
Для каждого сценария реализации сетевой атаки указывается состав и краткая характеристика основных объектов защиты. Для того, чтобы разработать план мероприятий по обеспечению безопасности Организации в части противодействия сетевой атаки типа необходимо учесть модель нарушителя (таблица Модель нарушителя с атрибутами: Идентификатор нарушителя, Тип нарушителя, Способ реализации (сценарий атаки), Способ реализации (уязвимость), Мотивация и цели нарушителя).
Перечень мероприятий по обеспечению безопасности Организации при сетевой атаке представляется в виде (таблицы Меры защиты информации с атрибутами: Последовательность и содержание действий злоумышленника, Меры защиты Организации от сетевой атаки) Формируется перечень мероприятий, включающий в себя требования и меры по защите информации с учетом специфики сетевой атаки. 
Организационная структура системы обеспечения информационной безопасности Организации представлена (в таблице Организационная структура системы обеспечения информационной безопасности Организации с атрибутами: Сценарии атаки, Должностные лица), где указывается перечень должностных лиц с их функциональными обязанностями в части противодействия сетевой атаке.
Текущий контроль за соблюдением выполнения требований Частной политики возлагается на ответственных за систему обеспечения информационной безопасности КС. Реализация и соблюдение мер защиты, регламентов и инструкций должно контролироваться на регулярной основе. Чтобы обеспечить эффективный контроль над выполнением требований определенных Частной политикой в зависимости от специфики сетевой атаки используется комплексная система мер и процедур, скоординированных и осуществляемых соответствующими службами Организации. Данная комплексная система мер и процедур состоит из действий, представленных в (таблице Комплексная система мер и процедур, отвечающая за контроль выполнения требований определенных Частной политикой с атрибутами: Предложенные меры безопасности в рамках противодействия сетевой атаке типа, Меры контроля), где указывается перечь мер и средств, необходимых для контроля выполнения требований определенных Частной политикой для защиты от сетевой атаки. 

## 3. Частные регламенты

Реализация процессов обнаружения и регистрации инцидентов безопасности достигается путем, формирования перечня сведений, состоящего из:­	контролируемых информационных ресурсов Организации; типов инцидентов, которые подлежат обнаружению и регистрации с указанием их уровней критичности и приоритетов
Контролируемые информационные ресурсы Организации в рамках защиты от сетевой атаки представлены в (таблице Перечень информационных ресурсов Организации  с атрибутами: Идентификатор информационного ресурса, Информационный ресурс, Состав,  Технические характеристики), где перечисляются состав и технические характеристики контролируемых ресурсов Организации, необходимые для выявления инцидентов.
Инциденты, которые могут возникнуть в ходе реализации сетевой атаки, классифицируются по типам, также приводится уровень критичности и приоритет инцидента безопасности (таблица Классификация инцидентов с атрибутами: Сценарии
атаки, Тип инцидента, Описание, Критичность, Приоритет инцидента). Для определения уровня критичности инцидента используется (таблица Уровень критичности инцидента с атрибутами: Значение, Критическое значение, Время реагирования, Описание). Приоритет инцидентов безопасности формируется на основе использования характеристик регистрируемых инцидентов (таблица Форма определения приоритета инцидента с атрибутами: Масштаб инцидента, Значимость контролируемых информационных ресурсов).
Последовательность реагирования и первоочередные меры представлены (в таблице Меры локализации инцидентов безопасности с атрибутами: Идентификатор инцидента, Произошедший инцидент, Последовательность реагирования, Первоочередные меры предотвращения), где указываются инциденты, которые могут произойти в ходе реализации сетевой атаки, последовательность реагирования на них, первоочередные меры предотвращения. Последовательность реагирования определяется с помощью (таблицы Порядок определения последовательности реагирования на инциденты с атрибутами: Последовательность реагирования, Уровень критичности, Приоритет инцидента).
После выполнения первоочередных мер защиты необходимо реализовать план мероприятий по противодействию сетевой атаки, который приведен в (таблице План мероприятий по противодействию сетевой атаки с атрибутами: №п/п,	Мероприятия по противодействию сетевой атаки, Срок исполнения, Дополнительно), где перечисляются мероприятия, которые направлены на устранение инцидентов безопасности с указанием срока исполнения.
Специалисты службы по работе с инцидентами должны выявить причины и условия возникновения инцидентов безопасности в Организации, ходе реализации сетевой атаки. Соотношение инцидентов безопасности с потенциально возможными причинами и условиями представлено (в таблице Причины и условия возникновения инцидентов безопасности с атрибутами: Инцидент безопасности, Причины и условия возникновения инцидентов безопасности).
 
## 4. Частные инструкции

Сотрудник обязан знать (таблица Функциональные знания с атрибутами: Должность, Сетевая атака, Необходимо знать). Указывается перечень требований к функциональным знаниям сотрудника, которыми он должен обладать, чтобы успешно защитить сеть Организации от различных векторов сетевой атаки. Сотрудник должен уметь (таблица Требования к умениям с атрибутами: Сетевая атака, Необходимо уметь). Указывается перечень требований к умениям Администратора, которыми он должен владеть, чтобы успешно защищать сеть Организации от векторов сетевой атаки.
Пример плана действий Администратора при выборе и настройке СЗИ приведен (в таблице Пример плана действий Сотрудника при выборе и настройке СЗИ с атрибутами: Выбор наиболее опасных сочетаний векторов атаки VA_i и уязвимостей VB_j, Требование к защите информации, Выбранное СЗИ, Рекомендация по настройке параметров).
Для построения разграничительной матрицы доступа Сотрудник должен следовать схеме. После чего сформировать матрицу, пример которой приведен (в таблице Пример разграничительной матрицы доступа с атрибутами: Объекты защиты, Роли пользователей). 

---
# Описание новых схем

## 1. Входные данные

Предыдущая схема входных данных работает только с одиночными атаками, что уже не является правильным подходом для проектирования организационно-правового обеспечения организации против современных комплексных атак. Следующая модернизированная схема организационно-правого обеспечения решает данную проблему.
В дальнейшем схемы будут разделены на 3 раздела, где 1 раздел отвечает за обозначение внешних данных, 2 раздел описывает какие алгоритмы использует разрабатываемое программное обеспечение, а 3 раздел обозначает ожидаемый результат программы.
В новой схеме входных данных внедрена генерация сведений для организационно-правового обеспечения. Внешние данные берутся с источников Mitre Att&ck, где по APT можно вывести перечень техник и этапов, по которым реализуется данная комплексная атака. Разрабатываемся программа для автоматизации входных данных для организационно-правового обеспечения использует программу Galeax-CVE2CAPEC. Благодаря этому становится возможным сгенерировать данные по CAPEC, CWE и CVE.

## 2. Частная политика

Предыдущая схема частной политики работает только с одиночными атаками, что уже не является правильным подходом для проектирования организационно-правового обеспечения организации против современных комплексных атак.
В модернизированной схеме частной политики также учтена работа программного обеспечения для генерации объектов защиты, меры противодействия, модели нарушителя и перечень должностей в отделе ИБ организации. Для объектов защиты в качестве внешнего источника данных используется Перечень объектов воздействия ФСТЭК. Данный выбор обусловлен вектором на информационную безопасность отечественных организаций, в чем специализируется ФСТЭК. Здесь ПО генерирует таблицу с объектами воздействия, по которым наиболее вероятно будет совершена определённая единичная атака.
Для мер противодействия в качестве внешнего источника данных используется Mitre Att&ck, в котором по указанной APT определены ссылки на меры противодействия. Здесь ПО генерирует таблицу с мер воздействия по указанным техникам APT.
Для Модели нарушителя из внешних источников целесообразно использовать данные реестра ФСТЭК. Другие необходимые данные модели, такие как Объекты воздействия, идентификаторы единичной атаки, уязвимости, уже сгенерированы программой, в результате чего не составит труда продублировать данные в данную таблицу.
Для Должностей ИБ используется фиксированный список должностей, который будет являться универсальным для организаций. Поэтому здесь ПО будет использовать всегда константные данные.

## 3. Частные регламенты

Предыдущая схема частных регламентов работает только с одиночными атаками, что уже не является правильным подходом для проектирования организационно-правового обеспечения организации против современных комплексных атак. Также предыдущая схема не учитывает риск-анализ атак. Данная проблема также учтена и решена в новой схеме.
В модернизированной схеме частных регламентов также учтена работа программного обеспечения для генерации инцидентов и регламентов, необходимых для противодействия данным инцидентам. Для генерации инцидентов и регламентов ПО использует калькулятор SSVC, который определяет данные по регламентам и инцидентам по результатам риск-анализа. В результате чего ПО выводит данные по инцидентам, регламенту Обнаружение и регистрация инцидентов, регламенту Реагирование на инциденты и регламенту Ликвидация последствий инцидентов.

## 4. Частные инструкции

Предыдущая схема частной инструкции работает только с одиночными атаками, что уже не является правильным подходом для проектирования организационно-правового обеспечения организации против современных комплексных атак.
В модернизированной схеме частной частных инструкций также учтена работа программного обеспечения для генерации объектов защиты, меры противодействия, модели нарушителя и перечень должностей в отделе ИБ организации. Для перечня СЗИ, необходимых для организации защиты безопасности от целевой атаки, в качестве внешнего источника данных используется реестр СЗИ ФСТЭК. Данный выбор обусловлен вектором на работу с отечественными средствами защиты информации, в чем специализируется ФСТЭК. Здесь ПО генерирует таблицу с перечнем СЗИ, по которым наиболее вероятно будет совершена APT атака. По результатам генерации ПО частной политики можно определить функциональные знания и умения, необходимые сотрудникам ИБ для использования СЗИ. В результате чего ПО генерирует разграничительную матрицу доступа, используя данные по объектам и сотрудникам, у которых определён уровень доступа к данному объекту. 

---
# Описание алгоритмов

## 1. Входные данные

### 1.1. Алгоритм Сбор данных Mitre Att&ck

Начало
Ввод APT.
ПО обращается к ресурсу https://attack.mitre.org/groups/
ID APT найдена?
если нет, то Вывод сообщения об ошибке поиска
Конец
если да, то Переход к данным APT
Получение списка techniques Mitre из таблицы Techniques Used
Вывод: список techniques Mitre
Конец

### 1.2. Алгоритм Генерация CAPEC

Начало
Ввод: № techniques Mitre
ПО обращается dataset techniques Mitre
№ techniques найдена?
если нет, то Вывод сообщения об ошибке поиска
Конец
если да, то ПО обращается dataset CAPEC
Результат Galeax-CVE2CAPEC
ID CAPEC найден?
если нет, то Вывод пустого значения
Конец
если да, то Получение ID CAPEC
Вывод: ID CAPEC
Конец

### 1.3. Алгоритм Генерация CWE

Начало
Ввод: ID CAPEC
ПО обращается dataset CAPEC
ID CAPEC найден?
если нет, то Вывод сообщения об ошибке поиска
Конец
если да, то ПО обращается dataset CWE
Результат Galeax-CVE2CAPEC
ID CWE найден?
если нет, то Вывод пустого значения
Конец
если да, то Получение ID CWE
Вывод: ID CWE
Конец

### 1.4. Алгоритм Генерация CVE

Начало
Ввод: ID CWE
ПО обращается dataset CWE
ID CWE найден?
если нет, то Вывод сообщения об ошибке поиска
Конец
если да, то Galeax-CVE2CAPEC обновляет dataset CVE
ПО обращается dataset CVE
Результат Galeax-CVE2CAPEC
ID CVE найден?
если нет, то Вывод пустого значения
Конец
если да, то Получение ID CWE
Вывод: ID CWE
Конец

## 2. Частная политика

### 2.1. Алгоритм Генерация объектов защиты

Начало
Ввод: CAPEC, CWE, URL базы объектов защиты
Установка соединения с сайтом https://bdu.fstec.ru/threat-section/objects через WEB драйвер
Успешное соединение?
если нет, то Попыток соединения >3?
если нет, то Установка соединения с сайтом https://bdu.fstec.ru/threat-section/objects через WEB драйвер
если да, то Сообщение об ошибке
Конец
если да, ПО обрабатывает через нейросеть записи с наибольшими совпадениями
Высокая точность результата?
если нет, то Сообщение об ошибке
Конец
если да, то Парсинг полученных данных
Создание файла csv таблицы "Объекты защиты"
Вывод: Вывод: файл CSV
Конец

### 2.2. Алгоритм Генерация мер противодействия

Начало
Ввод: Ввод: № techniques Mitre
ПО обращается к ресурсу https://attack.mitre.org/mitigations/
№ techniques Mitre найден?
если нет, Вывод сообщения об ошибке поиска
если да, то Переход к данным  techniques
Получение списка мер из таблицы  mitigations
Создание файла csv таблицы "Меры противодействия"
Вывод: Вывод: файл CSV
Конец

### 2.3. Алгоритм Генерация типов нарушителей

Начало
Ввод: Ввод: CAPEC, CWE, URL базы типов нарушителей
ПО обращается к ресурсу https://bdu.fstec.ru/threat-section/potential
Получение списка типов нарушителей
Создание файла csv таблицы "Модель нарушителя"
Вывод: Вывод: файл CSV
Конец

### 2.4. Алгоритм Список должностей

Начало
Ввод фиксированного списка сотрудников
Создание файла csv таблицы "Должности ИБ"
Вывод: Вывод: файл CSV
Конец

## 3. Частные регламенты

### 3.1. Алгоритм Генерация инцидентов

Начало
Ввод: CAPEC, CWE, результат калькулятора SSVC
ПО обращается к API SSVC для генерации списка инцидентов
Создание файла csv таблицы "Инциденты ИБ"
Вывод: Вывод: файл CSV
Конец

### 3.2. Алгоритм Генерация регламентов

Начало
Ввод: CAPEC, CWE, результат калькулятора SSVC, Инциденты
ПО обращается к API SSVC для генерации регламентов
Создание файла csv таблицы "Обнаружение и регистрация инцидентов"
Создание файла csv таблицы "Реагирование на инциденты"
Создание файла csv таблицы "Ликвидация последствий инцидентов"
Вывод: файлы CSV
Конец

## 4. Частные инструкции

### 4.1. Алгоритм Генерация требований

Начало
Ввод: Должности
ПО обращается к API нейросети для генерации функциональных знаний и требований к умениям
Создание файла csv таблицы "Функциональные знания и умения"
Вывод: файлы CSV
Конец

### 4.2. Алгоритм Генерация СЗИ

Начало
Ввод: CAPEC, CWE, URL базы СЗИ
Установка соединения с сайтом https://reestr.fstec.ru/reg3 через WEB драйвер
Успешное соединение?
если нет, то Попыток соединения >3?
если нет, то Установка соединения с сайтом https://reestr.fstec.ru/reg3 через WEB драйвер
если да, то Сообщение об ошибке
конец
если да, то ПО обрабатывает через нейросеть записи с наибольшими совпадениями
Высокая точность результата?
если нет, то Сообщение об ошибке
конец
если да, то Парсинг полученных данных
Создание файла csv таблицы "Описание функций выбранных СЗИ"
Вывод: файл CSV
Конец

### 4.3. Алгоритм Генерация РМД

Начало
Ввод: Должности, Объекты
ПО обращается к API нейросети для генерации РМД
Создание файла csv таблицы "Разграничительная матрица доступа"
Вывод: файл CSV
Конец

---
# Описание работы ПО

## 1. Входные данные

## 2. Частная политика

## 3. Частные регламенты

## 4. Частные инструкции


