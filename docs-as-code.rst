************
Docs-as-code
************

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

Мой опыт изучения
=================

Все изучить невозможно.

1. Выбрал генератор и язык разметки.
2. Придумал список задач, что хочу сделать с помощью инструмента.
3. Задокументировал свои действия в самом инструменте.
4. Выложил результат на GitHub Pages:

   - https://fish-train.github.io/flnt-test/
   - https://sph-learning.readthedocs.io/ru/latest/index.html
   - https://fish-train.github.io/DevOps_Docs/

С чего начать
=============

Определитесь с требованиями к вашей документации или учебному проекту:

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

Был доклад на TWD: Анжела Андронова. 

Язык разметки
-------------

Markdown
^^^^^^^^

Самый простой язык, но без спецификации, и с большим количеством диалектов:

- https://daringfireball.net/projects/markdown/syntax
- https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

ReStructuredText
^^^^^^^^^^^^^^^^

Язык разметки с единой спецификацией. 

- https://docutils.sourceforge.io/rst.html
- https://www.sphinx-doc.org/en/master/usage/restructuredtext/index.html
- https://www.writethedocs.org/guide/writing/reStructuredText/

AsciiDoc
^^^^^^^^

Язык разметки, специально разработанный для документирования: https://asciidoc.org/

- https://t.me/asciidoctor
- `Antora <https://antora.org/>`_
- `AsciiDoc & doc-as-code Best Practices <https://bcouetil.gitlab.io/academy/BP-asciidoc.html>`_
- https://habr.com/ru/articles/550086/
- https://newpodcast2.live/podcast/vanya-and-asiidoc/
- https://habr.com/ru/users/fiddle-de-dee/publications/articles/

Генераторы документации
-----------------------

- foliant, MkDocs, Docusaurus, они используют markdown
- Sphinx на reStructuredText и markdown
- Antora и Asciidoctor - у них asciidoc

Foliant
^^^^^^^

Foliant — это универсальный инструмент для создания документации. Он позволяет создавать отдельные документы в формате pdf и docx , создавать статические веб-сайты и загружать страницы в Confluence, и все это из одного источника Markdown.

Foliant использует другие программы для выполнения своей работы. Для создания pdf и docx можно использовать Pandoc или md-to-pdf, для веб-сайтов MkDocs, Aglio или Slate.

- https://foliant-docs.github.io/
- https://foliant-docs.github.io/docs/preprocessors/confluence/
- https://youtu.be/6CKVodl2YcA

Был доклад на TWD: Денис Ребенок.

MkDocs
^^^^^^

Еще один генератор на md: https://www.mkdocs.org/

Тема Material: https://squidfunk.github.io/mkdocs-material/

Был доклад на TWD: Никита Груздев. 

Hugo
^^^^

Пожалуй, самый быстрый генератор: https://gohugo.io/

Был доклад на TWD: Марсель Ардуанов.

Docusaurus
^^^^^^^^^^

Генератор доки на npm и react.js: https://docusaurus.io/

Gramax
^^^^^^

WYSIWYG-редактор с Git под катом и сборкой в HTML:

- https://gram.ax/
- https://t.me/gramax_chat

Был доклад на TWD: Александ Мачулин + Екатерина Павлова + Станислав Петров.

Diplodoc
^^^^^^^^

Использует Yandex Cloud:

- https://diplodoc.com/
- https://t.me/diplodoc_ru

Sphinx
^^^^^^

- https://www.sphinx-doc.org/en/master/
- https://www.youtube.com/watch?v=vFAkt_N6yuk&list=PLPDCBPbzk1AYghqYazE7Cxt3p7edml8I7
- https://www.youtube.com/watch?v=8Aydox51bfo&t=5s
- https://sublime-and-sphinx-guide.readthedocs.io/en/latest/index.html
- https://docs.readthedocs.io/en/stable/intro/getting-started-with-sphinx.html
- https://sphinx-ru.readthedocs.io/archive.html

Преимущества:

- `возможность перевода текстов из коробки <https://www.writethedocs.org/guide/writing/reStructuredText/>`_
- популярность
- `поддержка Markdown <https://myst-parser.readthedocs.io/en/latest/intro.html>`_
- выгрузка в различные форматы

Был мой доклад на TWD.

Еще-как-Код
===========

Презентации
-----------

Фреймворк Reveal.js для создания презентаций: https://revealjs.com/

Диаграммы и схемы
-----------------

- Mermaid: https://mermaid.js.org/
- Graphviz: https://graphviz.org/
- PlantUML: https://plantuml.com/ru/
