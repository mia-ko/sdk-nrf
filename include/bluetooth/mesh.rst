.. _bt_mesh:

Bluetooth mesh profile
######################

Bluetooth mesh is supported for development in |NCS|, through the Zephyr :ref:`zephyr:bluetooth_mesh` implementation.
It's a solution that allows one-to-one, one-to-many, and many-to-many communication, using the Bluetooth Low Energy protocol to exchange messages between the nodes in the network.
See the :ref:`Bluetooth mesh user guide <ug_bt_mesh>` for an overview of the technology.

Bluetooth mesh libraries contain modules provided by the Nordic Semiconductor to aid in the development of Bluetooth mesh-based applications.
They implement default behavior of a Bluetooth mesh device, and are used in :ref:`Bluetooth mesh samples <ble_samples>`.

For information on how to use the supplied libraries for Bluetooth mesh, see :ref:`ug_bt_mesh_configuring`.

.. toctree::
   :maxdepth: 1
   :caption: Subpages:

   mesh/model_types.rst
   mesh/models.rst
   mesh/properties.rst
   mesh/dk_prov.rst
   mesh/sensor.rst
   mesh/sensor_types.rst
