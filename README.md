#Ответ:
1. В GitHub:
* 1.1 Открываем репозиторий (чужой)
* 1.2 -> `Fork`
* 1.3 Убираем галочку с `Copy the main branch only`
* 1.4 -> `Create fork`
* 1.5 -> `Code`
* 1.6 Копируем ссылку
2. В терминале:
* 2.1 git clone <ссылка на репозиторий на GitHub>
* 2.2 cd <название репозитория>
* 2.3 git checkout -b <имя ветки>
* 2.4 git pull origin <имя ветки>
* 2.5 nano <название файла с вопросом>
* 2.6 git add <название файла>
* 2.7 git commit -m "комментарий"
* 2.8 git push origin <имя ветки>
3. В GitHub:
* 3.1 Переходим в репозиторий (чужой)
* 3.2 -> `Pull Requests`
* 3.3 -> `New pull request`
* 3.4 Затем нажимаем по выделенному тексту `compare across forks`
* 3.5 Выбираем откуда загружать:
*   3.5.1 нажимаем на `head repository` и выбираем наш репозиторий (личный)
*   3.5.2 нажимаем на `compare` и выбираем ветку
* 3.6 Выбираем ветку в которую загружаем, нажимаем на `base: main` и выбираем нужную ветку
* 3.7 -> `Create pull request`
* 3.8 В `Add a title` можем поменять комментарий
* 3.9 -> `Create pull request`

