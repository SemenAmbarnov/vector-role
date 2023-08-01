## Что делает плейбук

- Разворачивает на облаке 3 виртуальные машины: `Clickhouse`, `Lighthouse` и `Vector`. Конфигурирует их с помощью конфигов и установкой `Nginx` и выводит содержимое таблиц в `Lighthouse` в web-приложение.


## Параметры

Через group_vars можно задать следующие параметры:
- `lighthouse_vcs` - репозиторий для загрузки `lighthouse`;
- `lighthouse_location_dir` - место хранения дистрибутива `lighthouse`;
- `lighthouse_access_log_name` - имя файла логов для `nginx`;
- `clickhouse_version` - необходимая версия `clickhouse`;
- `clickhouse_packages` - необходимые пакеты `clickhouse`;
- `vector_url` - адрес для загрузки `vector`
- `vector_version` - необходимая версия `vector`;
- `nginx_user_name` - имя пользователя `nginx` по умолчанию;
- `ansible_host` - задаются ip VM;
- `ansible_ssh_user` - задаётся имя пользователя VM;
