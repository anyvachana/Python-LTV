# Python_rock

Задание:

To complete the task you need to calculate the LTV of cohorts of users for all available days, submit the notebook with calculations and a final csv file. Please, provide comments for your code and make sure it is reproducible.
Cohort means all players who installed the game on the same day. Cohort numeration in this task starts with 3001 (for players who installed on January 1st 2017)
LTV includes two sources - revenue from in-app purchases (IAP) and revenue from advertisments (Ads), which is a multiplication of total ads watched on a particular day by the corresponding eCPM, divided by 1000

LTV calculation formula:
http://joxi.ru/1A537a4IK996qm

Из данных: 
-Installs (оно же размер когорты),
-eCPM,
-Доход с внутриигровых трат (накопленной по дням для каждой когорты),
-Кол-во просмотренной рекламы (просто по когортам).
