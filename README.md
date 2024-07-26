# Предложения к оформлению корпоротивного GITHUB аккаунта

## Python
### Стили названий 

snake_case - для переменных, методов и функций
SCREAMING_SNAKE_CASE - для констант
PascalCase - для класов

### Базовый стек
requests, pydantic, aiogram3, django, fastapi, sqlalchemy, drf, drf-spectacular[swagger],
Simple JWT, django-rest-framework-jwt
celery(only linux|mac), channels, pydantic-settings, Jinja2, weasyprint(html to pdf)

### Остальной стек
aws - os, subprocess
google - google-cloud-bigquery, google-cloud-storage

psycopg2, pymongo (legacy)
neo4j (quantula)

### Тестовый стек
httpx

### Typing
str, int, list, tuple, set, bytes, dict, any, None
memoryview, frozenset, bytearray
'Class'(в рамках файла где объявлен этот класс), Path(при импорте из других файлов)
'self'(ссылка на себя)

### GIT
репозитории - kebab-case
ветки - kebab-case
коммиты/pull requests - XXX: normal text
feat: новый контент
fix: правки
init: инициализация
wip: в прогрессе

## JS, TS
### Стили названий

SCREAMING_SNAKE_CASE - для констант
PascalCase - для класов
camelCase - для методов и функций и переменных
TPascalCase - типы данных
IPascalCase - интерфейси
IProps - аргументы для компонента

### Базовый стек

pnpm, yarn

React, NextJS, Zod, Formik, axios, react-gtm-module, framer-motion, 
NextUI, shadcn, tailwind, eslint, prettier, lucide react,
netlify, vercel

React:
	- react-router-dom
	- redux / redux-toolkit / rtk-query
	- swr
	- react helmet
	- vite
	arrow components

NextJS:
	- nextjs14, src
	function components

GTM, GA4 (google), Microsoft Clarity, dataLayer

### Остальной стек

material-ui, clsx, react-slick-slider

### GIT
репозитории - kebab-case
ветки - kebab-case
коммиты/pull requests - XXX: normal text
feat: новый контент
fix: правки
init: инициализация
wip: в прогрессе

### Docs

шоб була)

### DEVOPS + administration

nginx(nodejs)
gunicorn

github actions

Docker
docker-compose

redis
posgresql
mongodb

uwf(firewall)
no ftp

ssh

------------
neo4j

### Payment

stripe

### Типы репозиториев
BackEnd FrontEnd как отдельные репозитории

