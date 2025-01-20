# Основные команды в Git


- **pwd** - покажет место где вы сейчас находитесь <br>
- **ls** - отобразит содержимое дириктории <br>
- **cd** - команда для перехода, например, чтобы перейти в нужную директорию необходимо написать cd и добавить название директории <br>
- **cd~** - перейти в домашнюю директорию <br>
- **touch** - для создания файла (после команда необходимо добавить название файла и его тип) <br>
- **mkdir** - для создания директории (папки) <br>
- **Хеш** - это идентификатор коммита, его уникальный номер
- **HEAD** - это файл в папке .git, в котором записана ссылка на последний коммит

                                                                    ##Какие бывают статусы файлов
- **untracked** - *неотслеживаемый, Git не следит за ним*
- **staged** - *спислк файлов которые войдут в коммит*
- **tracked** - *в него попадают файлы, которые уже были зафиксированы с помощью git commit, а также файлы, которые были добавлены в staging area командой git add. То есть все файлы, в которых Git так или иначе отслеживает изменения*
- **modified** - *cостояние modified значит, что Git сравнил содержимое файла с последней сохранённой версией и нашёл отличия. Например, файл был закоммичен и после этого изменён*