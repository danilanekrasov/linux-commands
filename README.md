| Команда | Параметры | Описание |
| ------- | --------- | -------- |
| pwd | | вывести путь к текущей директории  |
| cd | <путь> | перейти в указанную директорию  |
| chmod | +x <путь> | сделать файл исполняемым  |
| <путь к исполняемому файлу> | & | запустить программу в фоновом режиме  |
| wget | <ссылка> | скачать файл по ссылке и сохранить в текущую директорию  |
|  | |   |
| cat | <путь к файлу> | вывести содержимое файла в терминал  |
| less | <путь к файлу> | открыть файл на чтение (q - выход, / - поиск, g - в начало, G - в конец)  |
| nano | <путь к файлу> | открыть файл на редактирование (Ctrl + X - выход)  |
|  | |   |
| < | программа < файл | ввод данных в программу из файла через stdin  |
| > | программа > файл | вывод данных из программы в файл через stdout  |
| >> | программа >> файл | вывод данных из программы в файл c дозаписью через stdout  |
| 2> | программа 2> файл | вывод ошибок из программы в файл через stderr  |
| 2>> | программа 2>> файл | вывод ошибок из программы в файл c дозаписью через stderr  |
| \| | прог1 \| прог2 \| ... \| прогN | передача выходных данных программы на вход следующей программе  |
|  | |   |
| cp  | <путь1> <путь2> | скопировать файл 
| cp  | -r <путь1> <путь2> | скопировать директорию
| mv  | <путь1> <путь2> | переместить директорию или файл
|  | |   |
| rm  | <путь>  | удалить указанный файл
| rm  | -r <путь>  | удалить указанную директорию
| rm  | -rf <путь>  | удалить указанную директорию без подтверждения операции
|  | |   |
| mkdir  | <путь>  | создать указанную директорию
| mkdir  | -p <путь>  | создать указанную директорию и вышестоящие промежуточные директории
| touch  | <путь>  | создать файл
|  | |   |
| ls  |  | вывести содержимое текущей директории  |
| ls  | <путь>  | вывести содержимое указанной директории
| ls  | -a  | вывести содержимое вместе со скрытыми файлами
| ls  | -l  | вывести содержимое списком с размерами файлов в байтах, датой и правами
| ls  | -lh  | вывести содержимое списком с размерами файлов в Кб, Мб, Гб и т.д., датой и правами
|  | |   |
| man  | <команда>  | получить справку по указанной команде (клавиша "Q" для выхода)
| clear  |  | очистить экран терминала
| exit  |  | закрыть терминал

Специальные символы
| Символ | Описание |
| ------- | --------- |
| .    | текущая директория
| ..    | директория на уровень выше
| ~    | домашняя директория
|  | |   |
| *  | любое количество любых символов
| ?  |  один любой символ


Горячие клавиши
| Клавиши | Описание |
| ------- | --------- |
| Ctrl + A    | переставить курсор в начало строки
| Ctrl + E    | переставить курсор в конец строки
|  | |   |
| Ctrl + C  | прервать выполнение программы
| Ctrl + Z  |  приостановить выполнение программы
| Ctrl + Z, fg  |  продолжить выполнение приостановленной программы (с блокировкой терминала)
| Ctrl + Z, bg|  продолжить выполнение приостановленной программы  в фоновом режиме (в отдельном процессе) (терминал будет доступен)

