# Configuration-management-2
Конфигурационное управление, домашнее задание 2. Вариант №10
## Задание
Разработать инструмент командной строки для визуализации графа зависимостей, включая транзитивные зависимости. Сторонние средства для получения зависимостей использовать нельзя.

Зависимости определяются для git-репозитория. Для описания графа зависимостей используется представление PlantUML. Визуализатор должен выводить результат на экран в виде кода.

Построить граф зависимостей для коммитов, в узлах которого содержатся номера коммитов в хронологическом порядке.

Конфигурационный файл имеет формат toml и содержит:
- Путь к программе для визуализации графов.
- Путь к анализируемому репозиторию.
- Путь к файлу-результату в виде кода.


Все функции визуализатора зависимостей должны быть покрыты тестами.

## Содержание файла config.toml
```
[paths]
repo_path = "path_to_repo\\my_repo"
output_file = "path_to_repo\\output.puml"
```
Вместо path_to_repo нужно подставить путь к вашему репозиторию. 
## Результаты работы
В результате выполнения программы получим код в формате PlantUML, который можно преобразовать в рисунок. 


![alt text](http://www.plantuml.com/plantuml/png/ZP8zRWCX48LxJe6SsjB23Z_JH5PoaXaOaiZU9S9s5UNksLrHfAHx6lJUznLSxWzgZ-ToK_Vhr_fDZHQzrBMcprONqO_sb7ylQysYVvJMRvIk7wq-r_nURxNf5n7PpxLbQVtad5E_wgYSP3R4mPqqtNNF8MIVURPcBi5xWfImaCGG0qCq5csliYH2BaUrPu6IN4cc07dhVJ6C15D4T1CKWf3LA4EVpw_3grt8YK4JxI7KCzk9l4msumHRGT3E00usPYuPnB8QPUn2mwjTACQ4S-13g6StXs2sSPwIOsRAP3Y2Gx4-CZX2DShOXSPNBxBcxJFz0G00)
