.. caution:: 

    This repository has been archived. If you want to work on it please open a ticket in https://github.com/zopefoundation/meta/issues requesting its unarchival.


The ``z3c.recipe.paster:serve`` generates a paste deploy serve scripts and 
configuration files for starting a paste deploy based Zope 3 setup. The 
paste deploy ``*.ini`` file content can get defined in the buildout.cfg file.

Note, you have to define an entry_point in your projects setup.py file for
using a application_factory via the section name.
