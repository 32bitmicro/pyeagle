PyEAGLE - Read / Write EAGLE 6 Files
====================================

`Scott Torborg <http://www.scotttorborg.com>`_

PyEAGLE is an interchange API to read and write EAGLE 6 schematic, library, and
PCB layout files.


Installation
============

Install with pip::

    $ pip install pyeagle


Example Usage
=============

.. code-block:: python

    schematic = pyeagle.open('hello.sch')

    lib = pyeagle.open('SparkFun-Sensors.lbr')
    for part in lib:
        print part
