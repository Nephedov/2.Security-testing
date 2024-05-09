# «Инъекции и уязвимости на уровне ОС»

## Решения
#### Задание 1
* <a href="https://docs.google.com/spreadsheets/d/1w8mJnj_2N0bGjMxfvzpy_S0cbCgoCeONxBF0txHKrbk/edit?usp=sharing">Чек-лист</a> на 23 проверки полей ввода.

  
#### Задание 2
* <a href="https://docs.google.com/document/d/1op58oLiIFKADd2RQXfq1dRoxPNPR5W3KIMPNc-9kIh0/edit?usp=sharing">WhiteList</a> символьного поля ввода.

  
## Что было сделано
#### Задание 1
* Реализован <a href="https://docs.google.com/spreadsheets/d/1w8mJnj_2N0bGjMxfvzpy_S0cbCgoCeONxBF0txHKrbk/edit?usp=sharing">чек-лист</a> проверок двух полей:
  * Числового.
  * Символьного.
 
  
#### Задание 2
* Реализован <a href="https://docs.google.com/document/d/1op58oLiIFKADd2RQXfq1dRoxPNPR5W3KIMPNc-9kIh0/edit?usp=sharing">WhiteList</a> символьного поля.

## Описание Задания 1

Составить план тестирования приложения, имеющего два поля: 

1. Числовое — двухбайтная величина. Нужно проверить числовое переполнение. 
2. Символьное — строка до 50 символов. Нужно проверить на переполнение буфера и Input Validation.

## Описание Задания 2 

Предложить Whitelist для символьного поля, если известно, что в нём указывается путь, по которому следует получить список файлов.
