#  <center><u>Руководство по Git</u></center>
## <u>Основные команды</u>
### Настройки репозитория
* <font color="yellow"> git --version</font> - показывает установленную версию Git.
* <font color="yellow"> git init </font> - инициализирует локальный репозеторий.Команду выполняют только один раз для первоначальной настройки нового репозитория. Выполнение команды приведет к созданию нового подкаталога .git в вашем рабочем каталоге. Кроме того, будет создана новая главная ветка.
* <font color="yellow"> git clone</font> <font color="green">repo url</font> - выполняют для создания копии (клонирования) удаленного репозитория. 
*  <font color="yellow">  git add</font> <font color="green">Название файла</font>.<font color="yellow">Расширение файла</font> - добавляет содержимое рабочего каталога в индекс(staging area) для последующего коммита. Команда<font color ="yellow"> git add --all</font> добавляет все измененные и неотслеживаемые файлы в репозиторий и обновляет дерево изменений репозитория.
* <font color="yellow">git push</font> - отправляет изменения в удаленный репозиторий.
* Команда берёт все данные, добавленные в индекс с помощью <font color="yellow
">git add</font>, и сохраняет их
слепок во внутренней базе данных, а затем сдвигает указатель текущей ветки на этот слепок - <font color ="yellow
">git commit -m </font>"<font color="yellow">Teкст сообщения"</font>

* Журнал изменений, показывает количество сохранений - <font color="yellow
">git log</font>

* Переключение между версиями -<font color="yellow
"> git checkout</font>  <font color="yellow">номер коммита</font>

* Вернуться обратно к тому коммиту в котором работали - <font color="yellow
">git checkout master</font>
>  <font color="green">*Нажатие клавиши </font> <font color="yellow">"Q"</font> <font color="green"> возвращает в исходное окно терминала.*</font>

* Показывает разницу между текущим файломи сохранённым -  <font color="yellow
">git diff</font>

* [Статья](https://gb.ru/posts/soveti-pro-git) про папки, репозитории и некоторые сложности при освоении контроля версий от Ильнара Шафигуллина.
* Дополнительный [курс](https://gb.ru/courses/1117) по Git.











