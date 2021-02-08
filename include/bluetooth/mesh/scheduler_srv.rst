.. _bt_mesh_scheduler_srv_readme:

Scheduler Server
################

.. contents::
   :local:
   :depth: 2

The Scheduler Server model... describe the functionality...

The Scheduler Server model adds two model instances in the composition data:

* Scheduler Server
* Scheduler Setup Server

The two model instances share the states of the Scheduler Server, but accept different messages.
This allows for a fine-grained control of the access rights for the Scheduler Server states, as the two model instances can be bound to different application keys.

* Scheduler Server provides functionality for..
* Scheduler Setup Server provides functionality for...

Operation
=========



States
======

Name of state: ``reference``
   Explanation...

Name of state: ``reference``
   Explanation...

Extended models
===============



Persistent storage
==================

The Scheduler Server stores... persistently.



API documentation
==================

| Header file: :file:`include/bluetooth/mesh/scheduler_srv.h`
| Source file: :file:`subsys/bluetooth/mesh/scheduler_srv.c`

.. doxygengroup:: bt_mesh_scheduler_srv
   :project: nrf
   :members:
