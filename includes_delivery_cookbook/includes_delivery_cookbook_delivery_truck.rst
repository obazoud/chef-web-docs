.. The contents of this file may be included in multiple topics (using the includes directive).
.. The contents of this file should be modified in a way that preserves its ability to appear in multiple topics.


``delivery-truck`` is a cookbook for |delivery| that should be a dependency of every recipe in a ``build-cookbook``, which is effectively a project-specific wrapper cookbook for the ``delivery-truck`` cookbook.. The ``delivery-truck`` cookbook defines a set of recipes that correspond to the phases and stages in the |delivery| pipeline and help ensure good default ``build-cookbook`` behavior. |company_name| recommends including the ``delivery-truck`` cookbook in all recipes in a ``build-cookbook``.
