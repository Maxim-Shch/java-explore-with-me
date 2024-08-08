Приложение-афиша

Сервис позволяет пользователям обмениваться информацией об интересных событиях и найти компанию для участия в них.

Функиональность:

Для неавторизованных пользователей (публичное API):

Просмотр списка событий, отсортированных по количеству просмотров
Просмотр подробной информации о конкретном событии
Просмотр всех имеющихся категорий событий
Для авторизованных пользователей:

CRUD-операции событий
Возможность подать заявку на участие в интересующем событии
Возможность создателя мероприятия подтверждать заявки на участие в нем от других пользователей сервиса
Для администратора:

CRUD-операции категорий событий
CRUD-операции подборки мероприятий
Модерация событий, размещенных пользователями - публикация/отклонение
Технологический стек проекта: Java 11, Spring Boot, REST API, PostgreSQL, Hibernate ORM, Lombok, Docker, Swagger. Сервис имеет многомодульную структуру: основной сервис (работа с бизнес-логикой), сервис статистики (хранит количество просмотров и позволяет делать различные выборки для анализа работы приложения).

Для запуска сервиса в Docker нужно выполнить docker-compose.yml в IntelliJ IDEA.
