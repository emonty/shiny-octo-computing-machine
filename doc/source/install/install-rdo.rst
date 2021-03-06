.. _install-rdo:

Install and configure for Red Hat Enterprise Linux and CentOS
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


This section describes how to install and configure the pbrx service
for Red Hat Enterprise Linux 7 and CentOS 7.

.. include:: common_prerequisites.rst

Install and configure components
--------------------------------

#. Install the packages:

   .. code-block:: console

      # yum install

.. include:: common_configure.rst

Finalize installation
---------------------

Start the pbrx services and configure them to start when
the system boots:

.. code-block:: console

   # systemctl enable openstack-pbrx-api.service

   # systemctl start openstack-pbrx-api.service
