# Students_behavior_predict
Анализ активности студентов онлайн курса 'Введение в анализ данных в R' и построение моделей прогнозирования (классификации) успешности окончания курса студентами.

#### Задача:
На основании дата-сетов о действиях студентов в первые несколько дней построить модели для прогнозирования успешности окончания курса.

#### Технологии:
* Python==3.9
* Jupyter Notebook==6.5.4
* Pandas==2.0.3
* Sklearn==1.3.0

#### Описание исходных данных:

events_train.csv - данные о действиях, которые совершают студенты со стэпами
https://stepik.org/media/attachments/course/4852/event_data_train.zip
* step_id - id стэпа
* user_id - анонимизированный id юзера
* timestamp - время наступления события в формате unix date
* action - событие, возможные значения: 
* discovered - пользователь перешел на стэп
* viewed - просмотр шага,
* started_attempt - начало попытки решить шаг,
* passed - удачное решение практического шага

submissions_train.csv - данные о времени и статусах сабмитов к практическим заданиям
https://stepik.org/media/attachments/course/4852/submissions_data_train.zip
* step_id - id стэпа
* timestamp - время отправки решения в формате unix date
* submission_status - статус решения
* user_id - анонимизированный id юзера

#### Чтобы перезапустить вычисления:
* Клонировать репозиторий
  ```
  git clone git@github.com:ddr533/Students_behavior_predict.git  
  ```
* Перейти в папку с репозиторием
```
cd Students_behavior_predict
```
* Cоздать и активировать виртуальное окружение на Windows:

```
python -m venv env
env/scripts/activate
```
* Установить зависимости из файла requirements.txt:
```
pip install -r requirements.txt
```
* В командной строке запустить jupyter notebook
* Перейти в браузере на localhost
* Открыть main.ipynb
* Нажать кнопку RUN

#### Автор
Andrey D.
