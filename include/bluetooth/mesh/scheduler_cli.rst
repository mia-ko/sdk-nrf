.. _bt_mesh_scheduler_cli_readme:

Scheduler Client
################

.. contents::
   :local:
   :depth: 2

The Scheduler Client model remotely controls the state of a :ref:`bt_mesh_scheduler_srv_readme` model.

Unlike the Scheduler Server model, the Scheduler Client only creates a single model instance in the mesh composition data.
The Scheduler Client can send messages to both the Scheduler Server and the Scheduler Setup Server, as long as it has the right application keys.

Extended models
===============

None.

Persistent storage
==================

None.

API documentation
=================

| Header file: :file:`include/bluetooth/mesh/scheduler_cli.h`
| Source file: :file:`subsys/bluetooth/mesh/scheduler_cli.c`

.. doxygengroup:: bt_mesh_scheduler_cli
   :project: nrf
   :members:
