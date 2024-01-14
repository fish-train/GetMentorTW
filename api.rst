***
API
***

API – Application Programming Interface, программный интерфейс приложения. Набор инструкций, который позволяет разным приложениям общаться между собой. Набор фич, которые одна программа представляет всем остальным.

Типов API очень много. Важно понимать, что REST API - это популярный тип, но далеко не единственный.

- https://aws.amazon.com/ru/what-is/api/
- https://doka.guide/tools/api/
- https://practicum.yandex.ru/blog/chto-takoe-api/
- https://education.yandex.ru/journal/chto-takoe-api

REST API
========

REST - архитектурный стиль для API. Он определяет набор функций, таких как GET, POST, DELETE, которые клиенты могут использовать для доступа к данным сервера. Клиенты и серверы обмениваются данными по протоколу HTTP.

- `Курс по документированию REST API <https://starkovden.github.io/about-first-module.html>`_ и https://idratherbewriting.com/learnapidoc/
- https://events.yandex.ru/events/hyperbaton/msk-may-2014?openTalkVideo=440-3
- `О проектировании API <https://twirl.github.io/The-API-Book/API.ru.html>`_
- `Postman Tutorial <https://www.youtube.com/watch?v=juldrxDrSH0&list=PLhW3qG5bs-L-oT0GenwPLcJAPD_SiFK3C>`_
- https://stepik.org/course/124947/promo?search=3135701936

Примеры API
===========

Применение зависит от самого сервиса, который предоставляет API для своих клиентов.

Прогноз погоды и отображение в HTML
-----------------------------------

Запрос: https://openweathermap.org/current#fields_json

Нагрузочное тестирование
------------------------

Покажу пример локально

Проверка подключения кондиционера у Умному дому
-----------------------------------------------

https://yandex.ru/dev/dialogs/smart-home/doc/concepts/mode.html#discovery__example

Приложения VK для работы с фото
-------------------------------

https://dev.vk.com/ru/method/photos

Публичные API
-------------

- https://github.com/public-apis/public-apis

OpenAPI и Swagger
=================

OpenAPI – спецификация для описания REST API. Правила, по которым можно описать API к продукту в JSON- или YAML-форматах. Есть несколько версий. Они отличаются структурой и некоторыми тегами.

Ссылки:

- https://github.com/OAI/OpenAPI-Specification
- https://spec.openapis.org/oas/latest.html
- https://swagger.io/specification/

Swagger – набор инструментов для описания и визуализации API:

- `Swagger Codegen <https://swagger.io/tools/swagger-codegen/>`_. Генерирует код SDK клиента для множества различных языков. Software development kit - комплект для разработки программного обеспечения, помогает разработчикам реализовать API.
- `Swagger Editor <https://swagger.io/tools/swagger-editor/>`_. Онлайн-редактор, который проверяет документацию OpenAPI на соответствие правилам спецификации OpenAPI. Редактор Swagger помечает ошибки и дает советы по форматированию. Swagger Editor
- `Swagger UI <http://petstore.swagger.io/>`_. Веб-фрэймворк с открытым кодом, который парсит спецификацию OpenAPI и генерирует интерактивную страницу сайта с документацией.
- `SwaggerHub <https://swagger.io/tools/swaggerhub/>`_. Сайт, разработанный Smartbear, с целью помочь командам совместно работать над спецификацией OpenAPI. Помимо создания интерактивной документации из SwaggerHub, можно создавать множество клиентских и серверных SDK и других сервисов.

Подробнее:

- `Documenting APIs: A guide for technical writers and engineers <https://idratherbewriting.com/learnapidoc/openapi_tutorial.html>`_
- https://blog.skillfactory.ru/glossary/swagger/
- `Интеграция Swagger с документацией <https://fish-train.github.io/flnt-test/swagger/>`_ 
- `Интеграция Swagger с документацией <https://starkovden.github.io/integrating-swagger-with-docs>`_ 

Sphinx
======

Есть несколько расширений для генерации API-документации из спецификации:

- `sphinxcontrib-redoc <https://sphinxcontrib-redoc.readthedocs.io/en/stable/>`_ 
- `sphinxcontrib-openapi <https://sphinxcontrib-openapi.readthedocs.io/>`_ 
- `sphinxcontrib-sphinx-rest-api-doc <https://github.com/yishenggudou/sphinx-rest-api-doc>`_ 
- `sphinxcontrib.httpdomain <https://sphinxcontrib-httpdomain.readthedocs.io/en/stable/>`_ 

Дополнительные материалы
========================

- https://t.me/docsascode
- `ReadMe: How to Use OpenAPI and Swagger for Documentation <https://blog.readme.com/how-to-use-openapi-and-swagger-spec-for-documentation/>`_ 
- `ReDoc <https://github.com/Redocly/redoc>`_ 
- `ReDoc Demo <https://redocly.github.io/redoc/>`_ 
