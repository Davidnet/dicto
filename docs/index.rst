.. meta::
    :description: dicto a hashmap object in python designed for simplicity.

.. title:: dicto a hashmap object in python designed for simplicity.

Dicto. Make Hashmap Simple Again.
========================================

Version |version|.

----

dicto is a small library that provides a **Dicto** object, that acts as a hashmap
(dictionary alike) in which values are accessed via dot operator in python, i.e ``object.value``,
dicto also provides help functions to integrate **Dicto** objects to CLI frameworks 
such as *Fire* or *click* to make configs and params object more natural to access.

But that's enough chit-chat, let us show a simple example for dicto.

.. literalinclude:: ../test-fire.py
    :language: python

Observe that the combination of *dicto* and *fire* allows us to make a very simple CLI with a self-consistent params object.

As a basic function, we provide a load function that allows to read a config file in the following formats:

- YAML files
- XML files
- JSON files

Other configs files are just a pull request away!

.. py:function:: dicto.load(filepath[, as_dicto=True])

   Returns a `Dicto` object from reading a config file in any of the supported config extensions.
   Returns a `dict` if the config file is wanted as a dictionary.





.. toctree::
   :maxdepth: 2
   :caption: Contents:

   modules



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
