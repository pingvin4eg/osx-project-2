HabraReader - мобильный клиент для Хабра
=============

Приложение HabraReader является клиентом для мобильной версии сайта habrahabr.ru.
Оно обеспечивает доступ к материалам сайта с айфона без использования браузера, позволяя
просматривать и соохранять избранные статьи для последующего просмотра, производить поиск по хабратопикам,
уведомлять о появлении новых статей, просматривать и оставлять коментарии.

Целевой аудиторией приложения являются участники хабрасообщества и те кто читает статьи на хабре.

Пример сценария использования приложения: 
Приложение используется для чтения статей на хабре. Статьи можно добавлять в избранное для оффлайнового чтения.

Описание поведения:
При запуске приложение загружает данные с хабры (вьюшка с текстом "Loading...")
затем отображается основной вид состоящий из эмблемы хабра при нажатии на которую появляется таблица со 
списком последних постов (и поиском, но данном storyboard поиска пока нет) и таблицы в которой отображаются избранные посты.
При нажатии на строку таблицы - открывается вьюшка с содержимым поста.
Нажатием кнопки в правом верхнем углу пост можно добавит в избранное.
