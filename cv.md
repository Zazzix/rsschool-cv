# Alexander Shcherban

## Contact information

**Email:** a.sherbanfl@yandex.ru
**Telegram:** @glazixx
**Discrod:** Aleksandr Shcherban (@zazzix) (Zazzix#9083)

## About myself  

Feeling passionate about learning new things. Good comunicational skills.  
I’ve spent 1 year living and working abroad in China. Currently working as CSS representative.

## Education  

Bachelor's degree. Major: Teaching English and Chinese languages.  
HTML and CSS trainings.  
SQL. Shultais Education basic course.  

## Languages.  

Russian - Native
English  - C1
Chinese - HSK 3

## Skills

Jira
Confluence
SQL
Periscope

## Code example

```SQL
SELECT TIME_FORMAT(ca.date, '%H:%i') as time, CONCAT_WS(" ", m.first_name, m.last_name) as manager, CONCAT_WS(" ", cl.first_name, cl.last_name) as client, co.name as company, time_format(SEC_TO_TIME(ca.duration_sec), '%H:%i:%s') as duration 
FROM calls as ca 
RIGHT JOIN clients as cl ON cl.id = ca.client_id 
LEFT JOIN companies as co ON co.id = cl.company_id 
JOIN managers as m ON m.id = ca.manager_id 
WHERE month(ca.date)=4 and DAYOFMONTH(ca.date)=5;
```
