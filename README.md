# node.projectOne

Ссылка на проект: [node.projectOne](https://ko1p.github.io/node_one/ "Первые шаги в разработке приложения на express.js")

Текущая версия: **v0.0.2**

### Что это за проект?

Делаю первые шаги в node.js :sunglasses:
Создаю с помощью фреймворка express локальный север.

## Примеры запросов:

| Запрос | Ответ | 
|:----------------|:---------:|
| GET localhost:3000/users | JSON-список всех пользователей |
| GET localhost:3000/cards | JSON-список всех карточек |
| GET localhost:3000/users/8340d0ec33270a25f2413b69 | JSON-пользователя с переданным после /users идентификатором. Если такого нет, API должно возвращать 404 статус ответа и JSON:{ "message": "Нет пользователя с таким id" } |
| Несуществующий адрес | { "message": "Запрашиваемый ресурс не найден" } |

###  Используемые технологии:

- JS
- CSS
- HTML
- Git
- Webpack
- Node.js (express)
