# hw9
### ШАГ 1. Удаляем все пустые строки. Используем регулярное выражение \n\r заменяем все вхождения на \0
![](https://pp.userapi.com/c834301/v834301642/1509db/I0XjND1-dkA.jpg)
### затем удаляем все строки с пробелами. Используем регулярное выражение ^[ ]*$ заменяем все вхождения на \0
![](https://pp.userapi.com/c824501/v824501688/149e2d/4jPDGisDULw.jpg)
### Также можно использовать раздел правка - операции со строками - удалить пустые строки, содержащие символ пробела

### ШАГ 2. Находим всех князей и города, имя и название которых оканчивается на "слав". Используем регулярное выражение \b[А-Я][а-я]*слав[а-я]{0,3}\b всего упоминаний о князьях нашла 561
![](https://pp.userapi.com/c824410/v824410875/15701b/HkDV6k_ufIA.jpg)

### ШАГ 3. Находим все упоминания Новгорода. Используем регулярное выражение Нов.?город.?.? всего упоминаний Новгорода нашла 59
![](https://pp.userapi.com/c847016/v847016538/5fce8/nr1VJw0zic0.jpg)
