GitHub Reflog v1.3.21 (Русскоязычная версия)
=====================

Добро пожаловать в архив GitHub Reflog. Reflog является еженедельной хроникой
интересных и удивительных репозиториев, публикующейся в блоге GitHub 
от `Kenneth Reitz <https://github.com/kennethreitz>`_, одного из
стильных господ с `The Changelog <http://thechangelog.com>`_, имеющего тонну
`opensource-проектов <https://github.com/kennethreitz>`_.



Рекомендуемые репозитории этой недели
~~~~~~~~~~~~~~~~~~~~~~~~~

`devstructure/blueprint <https://github.com/devstructure/blueprint>`_
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

Это один из самых клёвых проектов среди тех, которые я видел в последнее время.

Проще говоря, Blueprint - сборщик конфигурации вашего сервера.
Он сканирует вашу систему, запоминает установленные пакеты из различных 
менеджеров (aptitude, ruby's gem, python's pip и т.д.), архивы с ПО, собираемым 
из исходников, конфигурационные файлы. Затем полностью запаковывает вашу
конфигурацию сервера в файл ``bootstrap.sh`` с приложенным архивом. Вы можете 
взять этот загрузочный пакет и запустить его в любом месте, чтобы повторить 
конфигурацию вашего сервера.

А теперь Blueprint вышел на новый уровень: он генерирует полные копии/манифесты 
для `Chef <https://github.com/opscode/chef>`_ и `Puppet <https://github.com/puppetlabs/puppet>`_ с помощью команды ``blueprint-create {-C | -P}``.

Конечно же, необходимо проверить качество резульатат такого копирования, но 
это определённо уже большой шаг в автоматизации ваших систем.

Bon appetit!



Удивительные репозитории этой недели
~~~~~~~~~~~~~~~~~~~~~~~~

`drbrain/meme <https://github.com/drbrain/meme/>`_
++++++++++++++++++++++++++++++++++++++++++++++++++

У вас есть мем? Meme - это удивительный Ruby-gem для генерации
изображений memegenerator.net из коммандной строки. Поддерживаются: SPARTA,
PHILOSORAPTOR, KEANU, TROLLFACE, и многое другое. 
Результаты определенно `стоит посмотреть <https://github.com/drbrain/meme/pull/13>`_.

::

    $ meme US_POINT 'I want you' 'to merge this'

.. image:: https://d3nwyuy0nl342s.cloudfront.net/img/5e625c6296a67da465ffccdb
    382e318a6af02d63/687474703a2f2f692e696d6775722e636f6d2f64527542422e6a7067



Замечательные репозитории
~~~~~~~~~~~~~~~~


-  `taitems/Aristo-jQuery-UI-Theme <https://github.com/taitems/Aristo-jQuery-UI-Theme>`_:
     Это не новый проект, но он привлек очень много внимания на этой неделе.
     Aristo - это `прекрасная <http://taitems.github.com/Aristo-jQuery-UI-Theme/>`_ тема оформления для `jQuery UI <https://github.com/jquery/jquery-ui>`_ 
     которая эмулирует элегантный стиль JavaScript-фреймворка `Cappuccino <https://github.com/280north/cappuccino>`_. 
     jQuery UI имеет плохую репутацию за то, что имеет меньше-чем-хочется тем 
     оформления для своих виджетов. Aristo стремится исправить это.

-  `brainsik/virtualenv-burrito <https://github.com/brainsik/virtualenv-burrito>`_:
     Этот проект упрощает настройку
     `virtualenv <https://github.com/pypa/virtualenv>`_/обертки в вашей среде
     разработки на Python. Спринтеры с PyCon 2011 на прошлой неделе потратили 
     кучу времени на настройку IDE перед тем, как могли начать разработку. Этот
     проект призван уменьшить подобные накладные расходы.

-  `maccman/ichabod <https://github.com/maccman/ichabod>`_:
     Этот проект позволяет запускать WebKit JavaScript тесты из командной строки. 
     В настоящее время он поддерживает Jasmine и QUnit тестирование. Он также 
     даёт вам интерактивную JavaScript-консоль, имеющую доступ к Ruby-стеку.



Перспективные репозитории
~~~~~~~~~~~~~~~


-  `twitter/commons <https://github.com/twitter/commons>`_:
     Внутренние библиотеки Twitter для JVM. Readme и инструкции по сборке ещё
     не написанны, но это выглядит как очень широкий набор библиотек. Включено 
     всё, начиная от `memcached <https://github.com/memcached/memcached>`_-интерфейса 
     до парсера аргументов командной строки. Почитайте `документацию <http://twitter.github.com/commons/apidocs/index.html>`_, 
     чтобы узнать больше.

-  `extend/cowboy <https://github.com/extend/cowboy>`_: 
     Это "Маленький, быстрый, модульный HTTP-сервер" на полностью на Erlang.
     Это амбициозный проект, находящийся в ранней стадии развития. 
     Новые разработчики приветствуются!


Обратная связь приветствуется! Отправляйте ваши вопросы, предложения, и
анонимные советы на reflog@kennethreitz.com.
Email для связи по поводу русскоязычной версии: alone.amper+reflog@gmail.com

--------------

Больше новостей о проектах с открытым исходным кодом, вы можете получить на
`The Changelog <http://thechangelog.com>`_ и
`github/explore <http://github.com/explore>`_.
