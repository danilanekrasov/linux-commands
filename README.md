| Команда | Параметры | Описание |
| ------- | --------- | -------- |
| pwd | | вывести путь к текущей директории  |
| cd | <путь> | перейти в указанную директорию  |
| chmod | +x <путь> | сделать файл исполняемым  |
| <путь к исполняемому файлу> | & | запустить программу в фоновом режиме  |
|  | |   |
| wget | <ссылка> | скачать файл по ссылке и сохранить в текущую директорию  |
| wget | -P <путь до директории> <ссылка> | скачать файл по ссылке и сохранить по указанному пути  |
| wget | -O <путь до файла> <ссылка> | скачать файл по ссылке и сохранить по указанному пути с указанным именем  |
| wget | -c <ссылка> | докачать файл загрузка которого прервалась  |
| wget | --spider <ссылка> | проверить доступность файла по ссылке  |
| wget | -i <текстовый файл> | скачать файлы по ссылкам из файла  |
| wget | -r -l <глубина> ссылка | рекурсивное скачивание файлов по ссылке на указанную глубину (по умолчанию 5)  |
| wget | -r -A <тип,тип,...,тип> ссылка | рекурсивное скачивание файлов только определенного типа по ссылке |
|  | |   |
| find | <папка> -name "<имя файла>" | найти файл в папке  |
| grep | "<строка>" <файл> | найти строку в файле  |
| grep | -с "<строка>" <файл> | посчитать кол-во вхождений строки  |
| grep | -r "<строка>" <папка> | найти строку во всех файлах в папке  |
|  | |   |
| unzip | <архив.zip> | распаковать архив zip |
| zip | <архив.zip> <файл1> <файл2>  ...| запаковать указанные файлы и (или) папки в архив |
| gunzip | <архив.gz> | распаковать архив gz с удалением исходного архива  |
| gzip | <файл> | запаковать файл с удалением исходного файла  |
| tar | -cvf <архив.tar> <файл1> <файл2>  ... | запаковать указанные папки и (или) файлы в архив без зжатия  |
| gzip | <архив.tar> | запаковать tar архив в архив.tar.gz с удалением исходного архива  |
| tar | -xvf <архив.tar> | распаковать tar архив  |
| tar | -xzvf <архив.tar.gz> | распаковать tar.gz архив (gunzip) |
| bzip2 | <файл> | упаковать  |
| bunzip2 | <архив.bz2> | распаковать bz2 архив|
| tar | -cjvf <архив.tar.bz2> <файл1> <файл2>  ... | запаковать  |
| tar | -xjvf <архив.tar.bz2> | распаковать tar.bz2 архив |
|  | |   |
| jobs | | список запущенных приложений в рамках текущей сессии в терминале |
| fg %<номер> | | продолжить выполнение программы с указанным номером |
| bg %<номер> | | продолжить выполнение программы с указанным номером в фоновом режиме |
| ps | | посмотреть свои процессы |
| top | | мониторнг всех процессов |
| top | -u <имя пользователя> | мониторнг процессов указанного пользователя |
| kill | <номер процесса> | завершить процесс |
| kill | -9 <номер процесса> | убить процесс |
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
| ssh  | логин@адрес -p порт | соединение через ssh
| ssh-keygen  |  | создание ключа
| ssh-add  |  | добавить ключ
|  | |   |
| scp  | -P порт логин@адрес_сервера:путь 1 путь2  | скопировать файл с сервера(путь1) на клиента (путь2)
| scp  | -P порт путь 1 логин@адрес_сервера:путь2  | скопировать файл с клиента(путь1) на сервер (путь2)
|  | |   |
| apt  | install программа  | установить пакет через apt
| apt  | remove программа  | удалить установленный пакет
| apt  | update | обновить информацию о доступных пакетах в репозитариях
| apt  | upgrade | установить новые версии установленных пакетов
| apt  | install --only-upgrade пакет | обновить только один указанный пакет
|  | |   |
| free  | -g | информация об оперативной памяти
| nproc  |  | колво ядер процессора
| lscpu  |  | информация о процессоре
|  | |   |
| man  | <команда>  | получить справку по указанной команде (клавиша "Q" для выхода)
| which  | <команда>  | вывести путь к указанной команде (программе)
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

vim
| Команды | Описание |
| ------- | --------- |
| vim    | 
| vim файл   | 
| vim файл1 файл2 файл3 ...  | 
| :q    | выход
| :help    | справка
| режим normal    | режим по умолчанию, любая клавиша воспринимается как команда
| режим insert    | режим режим ввода текста, выход черезе Esc, Ctrl+c
| режим visual    | режим выделения
| h,j,k,l    | перемещение по символам
| w,W    | перемещение в начало следующего слова
| e,E    | перемещение в конец следующего слова
| b,B    | перемещение в начало предыдущего слова
| 0    | перемещение в начало строки
| ^    | перемещение к первому непробельному символу
| $    | перемещение в конец строки
| gg    | перемещение в начало файла
| G    | перемещение в конец файла
| :21\<Enter>    | перемещение к указанной строке
| Ctrl+D, Ctrl+U    | вниз/вверх на N строчек, где N обычно пол-экрана
| x    | удаление символа под курсором
| X    | удаление символа перед курсором
| de    | удалить до конца текущего слова
| d$    | удалить до конца строки
| d5w    | удалить 5 слов
| dd    | удалить строку
| d10d    | удалить 10 строк
| i    | перейти в режим insert
| a    | сдвинуть курсор вправо и перейти в режим insert
| o    | вставить пустую строку снизу и перейти в режим insert
| O    | вставить пустую строку сверху и перейти в режим insert
| yy    | скопировать строку
| p    | вставить перед
| P    | вставить после
| /<текст>    | искать текст вперед (n - следующее вхождение, N - предыдущее)
| ?<текст>    | искать текст назад (n - следующее вхождение, N - предыдущее)
| :%s/<что ищем>/<на что меняем>/<флаги>    | поиск с заменой, g - много замен в строке, с - подтверждение
| u    | отменить последнее действие
| Ctrl+r    | вернуть омененное действие
| :w    | сохранить
| :wq    | сохранить и выйти
| :q!    | выйти без сохранения
| :w <файл>    | сохранить изменения в указанный файл



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

bash
| Команда | Описание |
| ------- | --------- |
| #!/bin/bash    | путь до интерпретатора
| echo "текст"    | вывести текст
| <имя>=<значение>    | создание переменной, любые символы кроме дефиса, пробела и слеша, не может начинаться с цифры
| #    | комментарий
| $<имя> или ${<имя>}    | обращение к переменной
| $1 $2 ... $n    | обращение к аргументам скрипта
| $0    | имя скрипта
| $#    | количество аргументов
| $?    | код возврата
| if [[ условие ]]    | условие ветвления
| then    | действие при выполнении условия
| fi    | конец ветвления
| -z <строка>    | проверка на пустую строку
| -n <строка>   | проверка на не пустую строку
| ==  или -eq  | равенство
| != или -ne  | не равенство
| -lt или <  | меньше
| -le  | меньше или равно
| -gt или >  | больше
| -ge   | больше или равно
| -e <путь>   | путь существует
| -f <путь>   | это файл
| -d <путь>   | это директория
| -s <путь>   | размер файла больше 0
| -x <путь>   | файл исполняемый
| !   | отрицание
| &&   | логическое И
| ||   | логическое ИЛИ
