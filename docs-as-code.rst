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

!!!!!!!!!!!!!!!!!

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

foliant
^^^^^^^

!!!!!!!!!!!!!!!!!!!

MkDocs
^^^^^^

!!!!!!!!

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
