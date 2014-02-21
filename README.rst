{{ project_name|title }} Documentation
{% for char in project_name|make_list %}#{% endfor %}##############


Delete this line and anything below it

django-project-skel
-------------------

How to use the skeletons:

Either download and run::

    django-admin.py startproject --template=/Your/path/to/django-project-skel myproject -epy -ehtml -erst -ebat -etxt --name Makefile

Or use it directly::

    django-admin.py startproject --template=https://github.com/kaleissin/django-project-skel/archive/master.zip myproject -epy -ehtml -erst -ebat -etxt --name Makefile

Author in the docs is hardcoded to "kaleissin" so sed it away with::

    sed -i "s/kaleissin/Your Name/g" docs/conf.py

Django wish-list: have author_name as part of the context
