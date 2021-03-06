List of codemodders
===================

If everything is setup properly, the list of Django Codemods should appear when running libCST's ``list`` command:

bash::

    > python3 -m libcst.tool list
    django_codemod.Django30Command - Resolve deprecations for removals in Django 3.0.
    django_codemod.Django40Command - Resolve deprecations for removals in Django 4.0.

Codemodders are organised following the Django `deprecation timeline page`_, listing all its deprecations by version.

.. _deprecation timeline page: https://docs.djangoproject.com/en/3.0/internals/deprecation/

Django 3.0
----------

This command should fix things `removed in Django 3.0`_.

.. _removed in Django 3.0: https://docs.djangoproject.com/en/dev/internals/deprecation/#deprecation-removed-in-3-0

.. autoclass:: django_codemod.commands.django_codemod.Django30Command
    :members:

Django 4.0
----------

This command should fix things `removed in Django 4.0`_.

.. _removed in Django 4.0: https://docs.djangoproject.com/en/dev/internals/deprecation/#deprecation-removed-in-4-0

.. autoclass:: django_codemod.commands.django_codemod.Django40Command
    :members:
