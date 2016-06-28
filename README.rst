.. contents::

Introduction
============

This offers documentation for Pyramid learning.

Pyramid
=======

http://pyramid-tutorials.readthedocs.io/en/latest/humans/
http://github.com/dnouri/pyramid-tutorial

Kotti
=====

It is recommended to install Kotti inside a virtualenv:

.. parsed-literal::

  $ virtualenv kotti_site
  $ cd kotti_site
  $ bin/pip install -r https://raw.github.com/Kotti/Kotti/stable/requirements.txt


Here is the sample message by the end of installation:

.. parsed-literal::

  Successfully installed Kotti Babel Beaker Chameleon FormEncode Mako
  MarkupSafe PasteDeploy Pillow Pygments SQLAlchemy SQLAlchemy-Utils
  Unidecode WebOb alembic appdirs bleach bleach-whitelist colander
  deform docopt fanstatic filedepot html2text html5lib iso8601
  js.angular js.bootstrap js.deform js.fineuploader js.html5shiv
  js.jquery js.jquery-form js.jquery-maskedinput js.jquery-maskmoney
  js.jquery-sortable js.jquery-tablednd js.jquery-timepicker-addon
  js.jqueryui js.jqueryui-tagit js.modernizr js.select2 js.tinymce
  kotti-tinymce lingua peppercorn plone.scale polib py-bcrypt
  pyramid pyramid-beaker pyramid-chameleon pyramid-debugtoolbar
  pyramid-deform pyramid-mailer pyramid-mako pyramid-tm pyramid-zcml
  pytz repoze.lru repoze.sendmail repoze.workflow repoze.zcml
  shutilwhich six transaction translationstring usersettings venusian
  waitress zope.component zope.configuration zope.deprecation
  zope.event zope.i18nmessageid zope.interface zope.schema
  zope.sqlalchemy python-editor

Get the configuration file ready for Paste Deploy to work. Here is the example file:

.. parsed-literal::

  $ wget https://raw.github.com/Kotti/Kotti/stable/app.ini

Often just change the `kotti.secret` and `host` settings and ready to go.

.. parsed-literal::

  $ bin/pserve app.ini

SubstanceD
==========

Working with Diazo? Unlike Plone, SubstanceD does not define any "retail" views.

Diazo
=====

https://github.com/ade25/kotti-blueprint

