************************************
Технологии для технического писателя
************************************

.. image:: faktorovich.jpg

API
===

Типов API очень много. Важно понимать, что REST API - это популярный тип, но далеко не единственный.

- https://aws.amazon.com/ru/what-is/api/
- https://doka.guide/tools/api/
- https://practicum.yandex.ru/blog/chto-takoe-api/
- https://education.yandex.ru/journal/chto-takoe-api

Полезные ссылки:

- `Курс по документированию REST API <https://starkovden.github.io/about-first-module.html>`_ и https://idratherbewriting.com/learnapidoc/
- https://events.yandex.ru/events/hyperbaton/msk-may-2014?openTalkVideo=440-3
- `О проектировании API <https://twirl.github.io/The-API-Book/API.ru.html>`_
- `Postman Tutorial <https://www.youtube.com/watch?v=juldrxDrSH0&list=PLhW3qG5bs-L-oT0GenwPLcJAPD_SiFK3C>`_
- https://stepik.org/course/124947/promo?search=3135701936

OpenAPI и Swagger
^^^^^^^^^^^^^^^^^

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

Инструменты для документирования REST API на основе OpenAPI спецификации:

- ReDoc: https://redocly.com/
- Slate: https://github.com/slatedocs/slate
  
Польза от изучения
^^^^^^^^^^^^^^^^^^

- попробовать на себе задачи разработчика
- стать ближе к разработчикам, говорить с ними на одном языке
- понимать, что нужно разработчикам в документации API

Облака
======

Попробовать развернуть какое-нибудь приложение на бесплатном тарифе: https://cloud.ru/ru/free-tier. Документация: https://cloud.ru/ru/docs/evolution/overview/topics/free-tier.html

- https://cloud.ru/ru/education/bystryj-start-advanced
- https://practicum.yandex.ru/ycloud/

Git
===

Сфокусируйтесь на базовых командах и операциях: add, commit, push, pull, rebase, разрешение конфликтов.

- https://git-scm.com/book/ru/v2
- https://htmlacademy.ru/blog/git/git-console
- https://githowto.com/ru
- https://learngitbranching.js.org/?locale=ru_RU

SQL
===

- https://karpov.courses/simulator-sql

Linux
=====

- https://stepik.org/course/762/promo?search=3848294913
- https://stepik.org/course/124646/promo?search=3848294914
- https://stepik.org/course/181507/promo?search=3848294919
- https://stepik.org/course/73/promo?search=3848294915
- https://rotoro.cloud/ld-courses/%d0%b1%d0%b0%d0%b7%d0%be%d0%b2%d1%8b%d0%b9-linux-%d0%bf%d1%80%d0%b0%d0%ba%d1%82%d0%b8%d1%87%d0%b5%d1%81%d0%ba%d0%b8%d0%b9-%d0%be%d0%bf%d1%8b%d1%82/#learndash-course-content

DevOps и DocOps
===============

Автоматизировать сборку своего учебного проекта по Docs-as-Code, например, в Github Pages: https://pages.github.com/

Польза от изучения:

- попробовать на себе задачи инженера
- стать ближе к инженерам, говорить с ними на одном языке
- понимать, что нужно инженерам в документации

Менее приоритетные вещи
=======================

Python
------

Язык, на котором написаны многие инструменты документирования, например, Foliant и Sphinx: 

- https://www.python.org/
- https://www.w3schools.com/python/default.asp
- https://karpov.courses/pythonzero

Польза от изучения:

- решение проблем с инструментами
- написание собственных утилит для автоматизации работы:
  
  - запуск локальных сборок
  - удаление неиспользуемых изображений из проекта доки

HTML
----

https://www.w3schools.com/html/default.asp

Польза от изучения: 

- решение проблем с сайтом документации
- редактирование шаблонов сборки документации

CSS
---

https://www.w3schools.com/css/default.asp

Польза от изучения: редактирование шаблонов сборки документации.

Javascript
----------

https://www.w3schools.com/js/default.asp

Польза от изучения: написание скрипта для своей доки. Например, добавить кнопку, которая копирует URL страницы.

Jinja
-----

HTML-шаблонизатор: https://jinja.palletsprojects.com/en/3.1.x/

Польза от изучения: редактирование шаблонов сборки документации.

ГОСТ
----

Знания ГОСТ 19, ГОСТ 34. 

Не нужно их знать наизусь, важно понимать, где найти нужную информацию по оформлению, структуре и содержанию документов.

Ссылки:

- https://gost34.ru/
- https://t.me/twriters
- http://www.rugost.com/

Польза от изучения:

- побороть страх перед ГОСТами, если он есть
- добавить строчку в резюме, если реально хочется этим заниматься
