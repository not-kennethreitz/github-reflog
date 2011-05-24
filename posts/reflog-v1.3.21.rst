GitHub Reflog v1.3.21
=====================

感谢您的阅读，这是 GitHub Reflog 的第一个版本。Github Reflog 每周为您
推荐托管在 Github 上的优秀项目。作者 `Kenneth Reitz <https://github.com/kennethreitz>`_ 是
`The Changelog <http://thechangelog.com>`_ 等一系列 `开源项目 <https://github.com/kennethreitz>`_ 的幕后黑手。



本周最佳
~~~~~~~~~~~~~~~~~~~~~~~~~

`devstructure/blueprint <https://github.com/devstructure/blueprint>`_
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

这是许久以来我所见过的最酷项目之一。

简单的说，Blueprint可以对服务器进行“反向工程”。它扫描您的系统，记录下通过包
管理器（aptitude，ruby 的 gem，python 的 pip）安装的，和自源代码编译安装的软
件，并记下配置文件的变更。最后将您整个服务器的配置打包成一个 ``bootstrap.sh`` 
文件和一个压缩包。通过者两个文件，您可以在任何服务器上精确地复制服务器配置。

此外，Blueprint 更进一步，它还可以通过 ``blueprint-create {-C | -P}`` 命令
生成 `Chef <https://github.com/opscode/chef>`_ 和 `Puppet <https://github.com/puppetlabs/puppet>`_ 格式的
自动配置脚本。

虽然最终生成的自动配置脚本的质量还需优化，但毫无疑问的是 Blueprint 是您平滑迁移
现有系统的首选工具之一。

好好享用吧！



本周优秀
~~~~~~~~~~~~~~~~~~~~~~~~

`drbrain/meme <https://github.com/drbrain/meme/>`_
++++++++++++++++++++++++++++++++++++++++++++++++++

Meme 是以命令行形式生成 memegenerator.net 图片的优秀 ruby gem。它支持 SPARTA，
PHILOSORAPTOR，KEANU，TROLLFACE 等等热门图片。此代码库的 Pull 请求页面 `灰常值得一看 <https://github.com/drbrain/meme/pull/13>`_。

::

    $ meme US_POINT 'I want you' 'to merge this'

.. image:: https://d3nwyuy0nl342s.cloudfront.net/img/5e625c6296a67da465ffccdb
    382e318a6af02d63/687474703a2f2f692e696d6775722e636f6d2f64527542422e6a7067



值得注意的
~~~~~~~~~~~~~~~~


-  `taitems/Aristo-jQuery-UI-Theme <https://github.com/taitems/Aristo-jQuery-UI-Theme>`_:
     这不是一个新项目，但在本周它得到了分外的关注。Aristo 是一个 `很漂亮的 <http://taitems.github.com/Aristo-jQuery-UI-Theme/>`_ 
     `jQuery UI <https://github.com/jquery/jquery-ui>`_ 主题。它模仿了 JavaScript 框架 `Cappuccino <https://github.com/280north/cappuccino>`_
     的简洁样式。对于主题风格上明显短板的 jQuery UI，Aristo 力求有所改变。

-  `brainsik/virtualenv-burrito <https://github.com/brainsik/virtualenv-burrito>`_:
     这个项目简化您在 Python 开发环境中设置 `virtualenv <https://github.com/pypa/virtualenv>`_/wrapper 时多花的那些功夫。
     在上周的 PyCon 2011 Sprint 中，太多人在环境设置上浪费了太多时间。这个项目旨在解决这种令人头疼的问题。

-  `maccman/ichabod <https://github.com/maccman/ichabod>`_:
     这个项目能够让您在命令行里流畅的进行 WebKit JavaScript 测试。目前提供对 Jasmine 和 QUnit 的支持。
     同时它提供了一个可以访问 Ruby 环境的交互式 JavaScript 控制台。



值得关注
~~~~~~~~~~~~~~~


-  `twitter/commons <https://github.com/twitter/commons>`_:
     Twitter 内部针对 JVM 的公共库。虽然 Readme 和编译指南仍没有写好，但看得出这是一个很全面的库，
     从 `memcached <https://github.com/memcached/memcached>`_ 接口到参数解释器等无所不包。详情
     情参看 `文档 <http://twitter.github.com/commons/apidocs/index.html>`_ 。

-  `extend/cowboy <https://github.com/extend/cowboy>`_: 
     这是一个完全由 Erlang 实现的 HTTP 服务器，轻量，快速且模块化。这是一个刚刚起步的新项目，极富野心，欢迎贡献者加入！


任何问题，建议，推荐都请发送至 reflog@kennethreitz.com，对您的反馈我深表感谢！

--------------

更多开源界新闻，请查阅 `The Changelog <http://thechangelog.com>`_ 和
 `github/explore <http://github.com/explore>`_ 。
