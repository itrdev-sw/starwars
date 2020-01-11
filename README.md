# Тестовое задание Star Wars Universe
 **Нужно написать SPA которое общается с открытой API, выводит список фильмов Star Wars и детальную информацию о каждом из них.**

Ссылка на API: https://swapi.co/documentation

Приложение должно содержать 2 страницы:
1. Главная страница (дефолтная) -> **/films**
    * При переходе на роут ***/*** приложение должно перенаправлять пользователя на ***/films***
    * Выводит список всех фильмов. Формат вывода - название фильма
    * Содержит поле поиска. Поиск нужно реализовать на стороне фронтэнда. Поиск по названию эпизода (поле ***title***). Если по результатам поиска ничего не найдено - вывести сообщение "No Results"
    * При клике на названию фильма должен происходить переход на страницу с информацией о фильме
2. Страница с информацией о фильме  -> **/films/:id** (:id -> поле ***episode_id***)
    * Список полей, которые нужны для вывода:
        * title
        * opening_crawl
        * director
        * producer
        * release_date

### Стек технологий:
   - React
   - React Router
   - Redux
   - Redux Saga, Redux Thunk (будет плюсом)
   - TypeScript (будет плюсом)
   - Для работы с API можно использовать библиотеку https://github.com/axios/axios либо другую, какую Вы знаете

### NOTES
   - Над дизайном и версткой сильно не замарачивайтесь, главное что бы выглядело читабельно. Можно использовать CSS фреймвокр https://purecss.io/ 
