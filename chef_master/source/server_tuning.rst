.. THIS PAGE DOCUMENTS Chef server version 12.3

=====================================================
Server Tuning
=====================================================

.. include:: ../../includes_server_tuning/includes_server_tuning.rst

.. note:: .. include:: ../../includes_notes/includes_notes_enterprise_chef_tuning.rst


Customize the Config File
=====================================================
.. include:: ../../includes_config/includes_config_rb_server.rst

Use Conditions
-----------------------------------------------------
.. include:: ../../step_config/step_config_add_condition.rst


Recommended Settings
=====================================================
.. include:: ../../includes_server_tuning/includes_server_tuning_general.rst

SSL Protocols
-----------------------------------------------------
.. include:: ../../includes_server_tuning/includes_server_tuning_nginx.rst

Optional Settings
=====================================================
The following settings are often used to for performance tuning of the |chef server| in larger installations.

.. note:: .. include:: ../../includes_notes/includes_notes_config_rb_server_must_reconfigure.rst

bookshelf
-----------------------------------------------------
.. include:: ../../includes_server_tuning/includes_server_tuning_bookshelf.rst

opscode-erchef
-----------------------------------------------------
.. include:: ../../includes_server_tuning/includes_server_tuning_erchef.rst

opscode-expander
-----------------------------------------------------
.. include:: ../../includes_server_tuning/includes_server_tuning_expander.rst

opscode-solr4
-----------------------------------------------------
.. include:: ../../includes_server_tuning/includes_server_tuning_solr.rst

Update Frequency
+++++++++++++++++++++++++++++++++++++++++++++++++++++
.. include:: ../../includes_server_tuning/includes_server_tuning_solr_update_frequency.rst

postgresql
-----------------------------------------------------
.. include:: ../../includes_server_tuning/includes_server_tuning_postgresql.rst

rabbitmq
-----------------------------------------------------
.. include:: ../../includes_server_tuning/includes_server_tuning_rabbitmq.rst

Analytics Queues
+++++++++++++++++++++++++++++++++++++++++++++++++++++
.. include:: ../../includes_server_tuning/includes_server_tuning_rabbitmq_analytics_queue.rst

.. include:: ../../includes_server_tuning/includes_server_tuning_rabbitmq_analytics_queue_settings.rst
