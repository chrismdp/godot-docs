.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the VisualScriptYield.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_VisualScriptYield:

VisualScriptYield
=================

**Inherits:** :ref:`VisualScriptNode<class_VisualScriptNode>` **<** :ref:`Resource<class_Resource>` **<** :ref:`Reference<class_Reference>` **<** :ref:`Object<class_Object>`

**Category:** Core

Brief Description
-----------------



Properties
----------

+----------------------------------------------------+-----------------------------------------------------+
| :ref:`YieldMode<enum_VisualScriptYield_YieldMode>` | :ref:`mode<class_VisualScriptYield_mode>`           |
+----------------------------------------------------+-----------------------------------------------------+
| :ref:`float<class_float>`                          | :ref:`wait_time<class_VisualScriptYield_wait_time>` |
+----------------------------------------------------+-----------------------------------------------------+

Enumerations
------------

  .. _enum_VisualScriptYield_YieldMode:

enum **YieldMode**:

- **YIELD_FRAME** = **1**
- **YIELD_PHYSICS_FRAME** = **2**
- **YIELD_WAIT** = **3**

Property Descriptions
---------------------

  .. _class_VisualScriptYield_mode:

- :ref:`YieldMode<enum_VisualScriptYield_YieldMode>` **mode**

+----------+-----------------------+
| *Setter* | set_yield_mode(value) |
+----------+-----------------------+
| *Getter* | get_yield_mode()      |
+----------+-----------------------+

  .. _class_VisualScriptYield_wait_time:

- :ref:`float<class_float>` **wait_time**

+----------+----------------------+
| *Setter* | set_wait_time(value) |
+----------+----------------------+
| *Getter* | get_wait_time()      |
+----------+----------------------+

