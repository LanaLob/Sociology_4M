# Приложения к статье
Этот репозиторий содержит два приложения к статье Жучкова С., Ротмистров А. Автоматическое извлечение текстовых и числовых веб-данных для целей социальных наук. Социология: методология, методы, математическое моделирование, 2020.

Файл `Sociology4m_Basics.ipynb` содержит объяснения и примеры использования базовых концепций программирования на Python.

Файл `Sociology4m_Web_scraping.ipynb` содержит коды, воспроизводящие пример сбора данных, представленный в статье.

Чтобы файлы корректно отображались, мы рекомендуем скачать их на компьютер, а не просматривать онлайн. Для скачивания перейдите к нужному файлу, нажмите на кнопку `Raw` наверху справа, в открывшемся окне выберите `Сохранить как` и уберите из расширения часть `.txt` (оставив только `.ipynb` в конце).

На рис. `Implicit_JSON.jpg` проиллюстрирована ситуация, когда веб-ресурс не предоставляет API, но некоторым неочевидным образом даёт доступ к своему JSON (описана в статье на с.10): сверху «невидимые технические процессы» в веб-инспекторе и снизу – код для обращения к обнаруженной странице, содержащей JSON. При загрузке страницы со списком фрилансеров из Китая на международной бирже freelancer.com  браузер также отправляет запрос на страницу с отдельными данными (адрес выделен красным в списке всех запросов слева; адрес не полный, т.к. домен опущен). Справа же во вкладке предпросмотра видно, как устроены данные по этому адресу. Для получения их с помощью кода достаточно отправить запрос на выделенный адрес (добавив перед неполным адресом домен) и извлечь из результата объект JSON.
