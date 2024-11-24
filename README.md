##Описание##
Эмулятор оболочки UNIX — это инструмент командной строки на Bash, который эмулирует работу оболочки UNIX-подобных операционных систем. Эмулятор предоставляет ограниченный набор команд (ls, cd, exit, cal, chmod, cat), работая с виртуальной файловой системой, основанной на содержимом tar-архива. Он запускается из реальной командной строки и работает в режиме CLI (Command Line Interface).

##Возможности##
Виртуальная файловая система: Эмулятор использует tar-архив для создания модели файловой системы во временной директории.
Изолированная среда: Все операции происходят внутри виртуальной файловой системы, исключая взаимодействие с реальной файловой системой пользователя.
Поддерживаемые команды:
ls: выводит список файлов и каталогов в текущей или указанной директории.
cd: изменяет текущую виртуальную директорию.
exit: завершает работу эмулятора и удаляет временную файловую систему.
cal: отображает календарь текущего месяца.
chmod: изменяет права доступа к файлу или каталогу внутри виртуальной файловой системы.
cat: выводит содержимое файла.
Требования
Операционная система: Ubuntu или другая UNIX-подобная ОС с установленным Bash.
Интерпретатор Bash: версия 4.0 или выше.
Необходимые утилиты: tar, ls, chmod, cal, cat, realpath, mktemp, read.
