<h1>Lara Airlines</h1>
<hr/>
<p>Пет-проект. Веб-приложение - создано для автоматизации бизнес процессов авиакпомнаий. В разработке..</p>
<h1>Технологии</h1>
<ul>
<li>Docker</li>
<li>ubunutu 20.04</li>
<li>nginx</li>
<li>Laravel 10.x</li>
<li>Vite</li>
<li>Vue 3</li>
<li>Postgresql 15.0</li>
<li>Tailwind</li>
<p>Будет дополняться...</p>
</ul>
<h1>Инструкция по развертыванию для OC Windows</h1>
<ul>
<li>Установить ubunutu 20.04 (Microsoft store) и настроить (user, password)</li>
<li>Установить Docker desctop и настроить(Убедиться что стоит флажок для использование WSL ubunutu 22.04)</li>
<li>Клонировать репозеторий(Чтобы был быстрый отклик клонируем в виртуальную систему WSL)</li>
<li>Открываем папку с проектом в нашей деректории через редактор(VScode, PHPstorm)</li>
<li>Запускаем терминал, убеждаемся что подключены с пользователя который создавался в 2-ом пункте</li>
<li>Поднимаем контейнеры: docker-compose up -d</li>
<li>Входим в основной контейнер: docker exec -it project_app bash</li>
<li>Входим в основной контейнер: docker exec -it project_app bash</li>
<li>Выдаем себе права и прописываем зависимости: chmod 777 -R storage/ && composer install && php artisan migrate && php artisan db:seed && npm install && npm run build</li>

<li>Начинаем разработку и коннектимся через браузер по адрессу: http://localhost/</li>

<p>Будет дополняться...</p>
</ul>