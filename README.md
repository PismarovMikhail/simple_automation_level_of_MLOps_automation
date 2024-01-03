# simple_automation_level_of_MLOps_automation

## Оглавление
### [1 Описание проекта](https://github.com/PismarovMikhail/simple_automation_level_of_MLOps_automation/edit/main/README.md)
### [2 Какой кейс решаем](https://github.com/PismarovMikhail/simple_automation_level_of_MLOps_automation/edit/main/README.md)
### [3 Краткая информация о данных](https://github.com/PismarovMikhail/simple_automation_level_of_MLOps_automation/edit/main/README.md)
### [4 Этапы работы над проектом](https://github.com/PismarovMikhail/simple_automation_level_of_MLOps_automation/edit/main/README.md)
### [5 Результат] (https://github.com/PismarovMikhail/simple_automation_level_of_MLOps_automation/edit/main/README.md)

### 1 Описание проекта


:arrow_up:[к оглавлению](https://github.com/PismarovMikhail/simple_automation_level_of_MLOps_automation/tree/main/README.md#Оглавление)

### 2 Какой кейс решаем

**Главная задача в реализуемом проекте — организация автоматизированного сбора данных, обработка этих данных, обучение модели ML и первичное тестирование.**
:arrow_up:[к оглавлению](https://github.com/PismarovMikhail/simple_automation_level_of_MLOps_automation/tree/main/README.md#Оглавление)

### 3 Краткая информация о данных



:arrow_up:[к оглавлению](https://github.com/PismarovMikhail/simple_automation_level_of_MLOps_automation/tree/main/README.md#Оглавление)

### 4 Этапы работы над проектом

- ***4.1 Организация автоматизированного сбора данных***
- ***4.2 Обработка данных***
- ***4.3 Обучение модели ML***
- ***4.4 Первичное теститрование***


:arrow_up:[к оглавлению](https://github.com/PismarovMikhail/simple_automation_level_of_MLOps_automation/tree/main/README.md#Оглавление)

### Результат


При реализации конвеера были созданы следующие **скрипты**:
- **get_data.py** Предназначен для получения данных из внешнего источника, платформы YouTube. Для этих целей используется API. По поисковому запросу «Mission Impossible» вы можете получить списки комментариев роликов YouTube, которые дает платформа по этому поисковому запросу. В полученном json файле можно достать значение параметра likeCount, которое и сохраняется в используемом далее наборе данных, в файле data.csv.
- **process_data.py** Этот скрипт предназначен для обработки данных, при которой полученные значения нормализуются, переводятся в диапазон от 0 до 1. Также в выходной файл записывается индекс значения.
- **train_test_split.py** Предназначен для разделения полученных и обработанных данных на тренировочную и тестовую выборки.
- **train_model.py** Предназначен для обучения модели ML.
- **test_model.py** Предназначен для тестирования модели ML.
- **youtube_comments_score.py** - Управление последовательностью операций по заданному расписанию.


:arrow_up:[к оглавлению](https://github.com/PismarovMikhail/simple_automation_level_of_MLOps_automation/tree/main/README.md#Оглавление)

