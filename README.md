GIT   

 

Команды:  

pwd - показать директорию, в которой находишься 

ls - отразить файлы и папки (ls –a - отражает также скрытые файлы конфигурации), также работает с ~ , .. 

cd - сменить директорию (если есть пробелы нужно использовать кавычки) можно использовать название с “/” - перемещение на несколько уровней 

cd ~ - вернуться в домашнюю директорию (папка пользователя) 

cd .. - вернуться в родительскую директорию  

cd c:/ - перемещение в корневую директорию 

 

touch %ИМЯ_ФАЙЛА%.расширение - создать файл 

mkdir %имя% - создание директории 

Можно создать целую структуру директорий одной командой с помощью флага -p 

mkdir -p dir1/dir-inside/dir-deeper-inside 

mv - перемещение файла  

cp - копирование ($ cp что_копируем куда_копируем $ cp index.html src/ 

Можно указать несколько файлов $ cp index.html style.css script.js src/) 

cat %имя% - чтение файла (только текстовые файлы) 

rm %имя%- удаление файла 

rmdir %имя% - удаление директории (только если она пуста) 

rm -r images - удаление папки со всеми файлами 

 

Инициализация репозитория 

git init (от англ. initialize, «инициализировать») — инициализируй репозиторий. 

Подготовка файла к коммиту 

git add todo.txt (от англ. add, «добавить») — подготовь файл todo.txt к коммиту; 

git add --all (от англ. add, «добавить» + all, «всё») — подготовь к коммиту сразу все файлы, в которых были изменения, и все новые файлы; 

git add . — подготовь к коммиту текущую папку и все файлы в ней. 

Создание коммита 

git commit -m "Комментарий к коммиту." (от англ. commit, «совершать», «фиксировать» + message, «сообщение») — сделай коммит и оставь комментарий, чтобы было проще понять, какие изменения внесены.  

Просмотр информации о коммитах 

git log (от англ. log, «журнал [записей]») — выведи подробную историю коммитов. 

Просмотр состояния файлов 

git status (от англ. status, «статус», «состояние») — покажи текущее состояние репозитория. 