# Ответы на вопросы экзамена "Математическая Логика и Теория Алгоритмов"
[Таблица со списком][1]

## Инструкции
### Правила
1. Стараемся уложиться в одну страницу.<br>
2. Выбираем незанятый вопрос из [таблицы][1] и вписываем свою фамилию в ней. <br>
3. В папке template есть docx файл, используйте его как шаблон.<br>
4. Название документа - двузначный номер вопроса (не 5, а 05).<br>
5. Сохранить его в docx и pdf форматах и сделать пулл реквест. В commit message название вопроса.<br>
6. Смотрите и проверяйте работы других.<br>
7. Ждем ревью и мержа.<br>

## Подробная инструкция по разработке (с помощью GitHub Desktop)
1. Делаем fork репозитория.<br>
2. Открываем GitHub Desktop.<br>
3. В левом верхнем углу через "File->Clone repository" находим fork-нутый репозиторий. Выбираем его, выбираем куда его склонировать и производим клонирование с помощью кнопки "Clone".<br>
4. Заходим в "Current branch" и создаем новую ветку с помощью "New branch". Название - номер вопроса (например, "16").<br>
5. Далее необходимо опубликовать данную ветку. Жмем по "Publish branch".
6. Работаем только с данным вопросом, копируем готовый документ в папку репозитория.<br>
7. В GitHub Desktop должны отобразиться изменения, он предложит вам сделать commit. Дайте commit'у вразумительное название и нажмите на "Commit to <название вашей ветки>". Далее сделайте "Push origin", чтобы ваши изменения попали в удаленную ветку. Так следует делать всегда, когда вы совершаете изменения.<br>
8. Переходим в репозиторий на сайт. Там должно отобразиться, что вы делали изменения в ветке. Далее 2 варианта:<br>
   1. GitHub предложит вам открыть pull request - для этого жмем по "Compare & pull request". Называем pull request также, как и название документа. Жмем по "Create pull request".<br>
   2. У вас не появилось данной кнопки. Тогда жмем по "New pull request". Слева должна быть выбрана ветка master, а справа ваша ветка. Назваем pull request также, как и название документа. Жмем по "Create pull request".<br>
9. Вы сделали pull request. Теперь можете ткнуть в своих соседей, чтобы они провели рецензирование. В случае каких-то замечаний, необходимо будет поправить документ.<br>
10. После того, как ваша ветка будет merge'нута в мастер, сходите в [таблицу][1] и отметьте, что вы сделали данный вопрос.<br>

<!-- LINKS -->
[1]: https://docs.google.com/spreadsheets/d/1GM_Oi23mgJdevG44jzeDZ28A8xBUvFo-I4W5lITa8Sw/edit?usp=sharing
