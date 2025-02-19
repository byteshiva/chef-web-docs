=====================================================
About the |dsl delivery|
=====================================================

.. include:: ../../includes_dsl_delivery/includes_dsl_delivery.rst

.. warning:: These recipe helpers are available from the ``delivery-truck`` cookbook: https://github.com/opscode-cookbooks/delivery-truck. This cookbook is a recommended dependency for any ``build-cookbook`` for a project that publishes changes to a |delivery| pipeline.

Helpers
-----------------------------------------------------
.. include:: ../../includes_dsl_delivery/includes_dsl_delivery_helpers.rst

.. 
.. node['delivery'] Attributes
.. -----------------------------------------------------
.. .. include:: ../../includes_dsl_delivery/includes_dsl_delivery_attributes.rst
.. 

Examples
-----------------------------------------------------
The following examples show how to use the |dsl delivery| in a cookbook:

**changed_cookbooks**

.. include:: ../../includes_dsl_delivery/includes_dsl_delivery_example_changed_cookbooks.rst

**bumped_version?**

.. include:: ../../includes_dsl_delivery/includes_dsl_delivery_example_bumped_version.rst

**push_repo_to_github?**

.. include:: ../../includes_dsl_delivery/includes_dsl_delivery_example_push_repo_to_github.rst
