************
Docs-as-code
************

   Внедрение подхода doc-as-code

   - Есть непонимание с чего начать, на что обратить внимание и какие ошибки лучше не совершать. Интересно узнать про опыт внедрения, так как сама в этом новичок.
   - Рекомендации по выбору инструментов.

Полезные ссылки
===============

Общая информация
----------------

- https://t.me/docsascode
- https://www.youtube.com/watch?v=1CuMeMYwtbg
- https://www.youtube.com/watch?v=8Aydox51bfo
- https://www.youtube.com/watch?v=6CKVodl2YcA
- https://www.youtube.com/watch?v=1CuMeMYwtbg
- https://youtu.be/ok9KMRCbrq8
- https://youtu.be/xqev76iddio
- https://jamstackthemes.dev/
- https://jamstack.org/generators/
- https://starkovden.github.io/Doc-as-code-tools.html
- https://habr.com/ru/companies/plesk/articles/555110/
- https://starkovden.github.io/Static-site-generators.html

Asciidoc
--------

- https://t.me/asciidoctor
- `Antora <https://antora.org/>`_
- `AsciiDoc & doc-as-code Best Practices <https://bcouetil.gitlab.io/academy/BP-asciidoc.html>`_
- https://habr.com/ru/articles/550086/
- https://newpodcast2.live/podcast/vanya-and-asiidoc/
- https://habr.com/ru/users/fiddle-de-dee/publications/articles/

Confluence
----------

- https://habr.com/ru/articles/483898/
- https://github.com/sphinx-contrib/confluencebuilder/
- https://github.com/asciidoctor/asciidoctor-confluence

С чего начать
=============

Определитесь с требованиями к вашей документации:

- Выходной формат: HTML, DOCX, PDF или другие
- Если нужен HTML, то какие фичи должны быть в статическом сайте
- Требования к оформлению
- Перевод на другие языки
- Интеграция с Confluence
- Переиспользование контента
- Будет ли описание API?
- ГОСТ?

Выбор инструмента
=================

Язык разметки
-------------

Markdown
^^^^^^^^

Самый простой язык, но без спецификации, и с большим количеством диалектов:

- https://daringfireball.net/projects/markdown/syntax
- https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

ReStructuredText
^^^^^^^^^^^^^^^^

Язык разметки с единой спецификацией: https://docutils.sourceforge.io/rst.html

AsciiDoc
^^^^^^^^

Язык разметки, специально разработанный для документирования: https://asciidoc.org/

Генераторы документации
-----------------------

- foliant, MkDocs, Docusaurus, они используют markdown
- Sphinx на reStructuredText
- Antora и Asciidoctor - у них asciidoc

Foliant
^^^^^^^

Foliant — это универсальный инструмент для создания документации. Он позволяет создавать отдельные документы в формате pdf и docx , создавать статические веб-сайты и загружать страницы в Confluence, и все это из одного источника Markdown.

Foliant использует другие программы для выполнения своей работы. Для создания pdf и docx можно использовать Pandoc или md-to-pdf, для веб-сайтов MkDocs, Aglio или Slate.

- https://foliant-docs.github.io/
- https://foliant-docs.github.io/docs/preprocessors/confluence/

MkDocs
^^^^^^

Еще один генератор на md: https://www.mkdocs.org/

Тема Material: https://squidfunk.github.io/mkdocs-material/

Hugo
^^^^

Пожалуй, самый быстрый генератор: https://gohugo.io/

Docusaurus
^^^^^^^^^^

Генератор доки на npm и react.js: https://docusaurus.io/

Sphinx
^^^^^^

https://www.sphinx-doc.org/en/master/

Преимущества:

- возможность перевода текстов из коробки
- популярность
- поддержка Markdown
- выгрузка в различные форматы

Мой опыт
========

Продукту, над которым я работаю, нужны:

1. Приличный сайт с документацией
2. Перевод на другие языки
3. Встраивание сборки документации в сборку самого продукта
4. Переиспользование контента
5. Документация API
6. Сборка docx, хоть и редко
7. Единый источник и сборка нескольких вариантов документации: cloud и enterprise, русский и английский языки

Желательно чтобы инструменты были бесплатными. Gitlab у разработчиков уже был.

Sphinx все мои задачи решил. Правда, понадобилось время, чтобы изучить и настроить так, чтобы все работало.
