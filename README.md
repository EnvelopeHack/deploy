## Деплой  
0. Для билда фронтенда и бэкенда нужны `Maven` и `npm` с `nodejs` и еще нужен `Docker`
1. Сделайте клон в `/backend` и `/frontend` из соответствующих [репозиториев](https://github.com/orgs/EnvelopeHack/repositories)
2. В `backend`:
```
mvn clean package
```
3. В `frontend`:
```
npm run build
```
4. В корневой папке:
```
docker compose up -d
```
5. Готово
