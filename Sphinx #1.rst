*********
Sphinx #1
*********

1. Структура каталогов
======================
  
     Я планирую разделять исходники по каждому продукту на подкаталоги. 
     Необходимо в каждом подкаталоге размещать conf.py и index.rst? 
     В этом плане не совсем понимаю, как разместить на одном портале описание по трем продуктам, если в каждом каталоге с rst исходниками должны быть конфигурационные файлы с настройками сборки.

Если необходимо собирать документацию по отдельному продукту, то у каждого продукта должен быть свой conf.py. Конфиг будет хранить настройки для сборки доки конкретного продукта. В команде сборки нужно будет указать путь к конфигу в ключе `-c`.

Также для отдельных сборок в конфиге нужно заполнить параметр `master_doc`. В нем указывается условный index.rst. Условный - потому что имя файла может быть любым.

Если отдельных сборок по продуктам не будет, то конфиг не нужно создавать.

Полезные ссылки:

- https://www.sphinx-doc.org/en/master/usage/configuration.html#confval-master_doc
- https://www.sphinx-doc.org/en/master/man/sphinx-build.html#cmdoption-sphinx-build-c

  
2. Как в меню-панели создать древовидную структуру с разделами
==============================================================
     
     - продукт1:
       - Общее описание;
       - Архитектура;
       - Функциональные возможности;
       - Руководство администратора;
       - Справочник API
       - и т.д.
     - продукт2:
       - Общее описание;
       - ...

В index.rst добавь toctree::

  .. toctree::
     :maxdepth: 1
     :caption: продукт1
     :hidden:
  
     product_1/topics/topic1
     product_1/topics/topic2
  
  .. toctree::
     :maxdepth: 1
     :caption: продукт2
     :hidden:
  
     product_2/topics/topic1
     product_2/topics/topic2

Полезные ссылки:

- https://www.sphinx-doc.org/en/master/usage/restructuredtext/directives.html#directive-toctree

3. Примеры проектов
===================

  Есть ли в открытом доступе на github пример проекта/базы знаний на базе Sphinx и темы Read the Docs или с другой темой? Или может у тебя есть такой пример. Так было бы проще разбираться.

- https://github.com/readthedocs/readthedocs.org/tree/main/docs
- https://github.com/readthedocs/sphinx_rtd_theme/tree/master/docs
- https://github.com/pradyunsg/furo/tree/main/docs
- https://github.com/tarantool/doc
- https://www.sphinx-doc.org/en/master/examples.html
- https://github.com/MarkHoeber/sublime_sphinx_guide/tree/master

Можно искать какие-то фрагменты кода по всем репозиториям в gшергию Например, как используется какой-то параметр в conf.py.

4. Автосборка
=============

  Как настроить автосборку и публикацию по сетевому адресу.

- https://www.jareddillard.com/blog/continuous-deployment-of-a-sphinx-website-with-using-jenkins-and-docker
- https://gitlab.com/pages/sphinx
- https://www.sphinx-doc.org/en/master/tutorial/deploying.html

У меня на проекте:

1. Разработчики настраивают пайплайн сборки всего продукта в Jenkins.
2. Я даю разработчикам команду сборки. Например::

   sphinx-build -b dirhtml source build/html/ent/ru -d build/doctrees/ru/ -t ent -D language=ru

   Сборка HTML на русском языке для Enterprise версии продукта

3. Разработчики сами правят пайплайн.

5. Что можно менять в теме. Например, кнопки, логотип (верхний правый угол)
===========================================================================

Настройки Sphinx
----------------

https://www.sphinx-doc.org/en/master/usage/configuration.html#options-for-html-output

Логотип устанавливается в параметре html_logo.

Настройки темы
--------------

Примеры:

- https://sphinx-rtd-theme.readthedocs.io/en/stable/configuring.html#theme-options
- https://pradyunsg.me/furo/customisation/

В Furo есть переменные, которые отвечают за оформление элементов страницы::

  html_theme_options = 
  	{
  		"sidebar_hide_name": True,
  		"navigation_with_keys": True,
  		"light_css_variables": 
  			{
  				"color-sidebar-background": "#F4F8FF",
  			}
  	}

Подключение собственных CSS- и JS-файлов
----------------------------------------

В conf.py::

  html_static_path = ['_static',]

  html_css_files = ['css/custom.css',]

  html_js_files = ['js/custom.js',]

В проекте:

Переопределение шаблонов темы
-----------------------------

В conf.py::

  templates_path = ['_templates']

В репозитории темы:

В проекте:

Полезные ссылки
===============

- https://t.me/docsascode
- https://awesomesphinx.useblocks.com/index.html
- https://documatt.com/blog/21/sphinx-conf-py-tips/
- https://sphinx-design.readthedocs.io/en/latest/
