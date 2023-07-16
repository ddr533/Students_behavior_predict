# Students_behavior_predict
Анализ активности студентов онлайн курса Введение в анализ данных в R и построение моделей прогнозирования успешности окончания курса студентами.

#### Задача:
На основании дата-сетов о действиях студентов в первые несколько дней построить модели для прогнозирования успешности окончания курса.

#### Технологии:
* Python
* Jupyter Notebook
* Pandas
* Sklearn
  
#### Описание исходных данных:

events_train.csv - данные о действиях, которые совершают студенты со стэпами
https://stepik.org/media/attachments/course/4852/event_data_train.zip
step_id - id стэпа
user_id - анонимизированный id юзера
timestamp - время наступления события в формате unix date
action - событие, возможные значения: 
discovered - пользователь перешел на стэп
viewed - просмотр шага,
started_attempt - начало попытки решить шаг,
passed - удачное решение практического шага

submissions_train.csv - данные о времени и статусах сабмитов к практическим заданиям
https://stepik.org/media/attachments/course/4852/submissions_data_train.zip
step_id - id стэпа
timestamp - время отправки решения в формате unix date
submission_status - статус решения
user_id - анонимизированный id юзера
