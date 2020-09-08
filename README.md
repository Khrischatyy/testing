
Запрос для вывода будет выглядеть следующим образом:

SELECT skills.name,skills.type,users.name,skills.frequency_of_use, add_time FROM experience_table LEFT JOIN skills ON skill_id = skills.id LEFT JOIN users ON user_id = users.id 
