[![Java CI with Gradle](https://github.com/alexdnf/DemoCI-CD/actions/workflows/%20gradle.yml/badge.svg)](https://github.com/alexdnf/DemoCI-CD/actions/workflows/%20gradle.yml)

# Заготовка бэкэнда банковского приложения
### Необходимо протестировать:

Эндпоинт http://localhost:9999/api/v1/demo/accounts

### Требования:
* 200 Status code
*  В теле ответа возвращается JSON файл
*  В теле ответа содержится массив, состоящий из трех объектов (банковских счетов)
*  Проверка валюты каждого из счетов (currency в Json-схеме)
   - RUB
   - USB
   - RUB

## Развернуть приложение можно с помощью Jenkins и pipline, описанного в Jenkinsfile
