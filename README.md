ссылка на игру в роблокс  https://www.roblox.com/games/15217885410/Others-in-the-room
flowchart TD
    A[Получение HTTP-запроса] --> B{Это GET или POST?}
    B -->|GET| C[Поиск маршрута]
    B -->|POST| D[Парсинг тела запроса]
    C --> E[Вызов обработчика GET]
    D --> F[Вызов обработчика POST]
    E --> G[Отправка ответа]
    F --> G[Отправка ответа]
