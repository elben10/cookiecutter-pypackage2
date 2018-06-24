{% set title = "Welcome to " + cookiecutter.project_name + "'s documentation!" %}{{ title }}
{% for i in title %}={% endfor %}

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   readme
   installation
   usage
   modules
   contributing
   {% if cookiecutter.create_author_file == 'y' -%}authors
   {% endif -%}history

Indices and tables
==================
* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
