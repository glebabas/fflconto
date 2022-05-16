## fflconto for Food For Fife
-Консольное приложение для обработки данных в базе Пищи Жизни
-
-

# Запуск


# Справочник команд
`--database=<path>` - нахождение папки базы данных
`fflconto dict income add --code=<code> --name=<name> [--comment=<comment>]` - добавление строчки в текстовом файле dict-income.csv отвечающего за доходы
`fflconto dict income update <code> [--name=<name>] [--comment=<comment>] [--code=<code>]` - изменение строчки в текстовом файле dict-income.csv отвечающего за доходы
`fflconto dict income delete <code>` - удаление строчки в текстовом файле dict-income.csv отвечающего за доходы
`fflconto dict income show <code>` - показание записи по коду в текстовом файле dict-income.csv отвечающего за доходы в формате **code, name, comment**
`fflconto dict income list` - показание всех записей словаря в построчном виде