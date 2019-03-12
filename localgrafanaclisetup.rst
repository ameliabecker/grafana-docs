******************************************
Local Grafana Setup
******************************************

Influxdb
========
Installing
----------
uses ports 8086
`download instructions`_ 

.. _download instructions: https://docs.influxdata.com/influxdb/v1.7/introduction/installation/

.. code-block:: bash

    brew install influxdb


Grafana Local
=============

`Official Grafana Docs`_ 

.. _Official Grafana Docs: http://docs.grafana.org/

`Download Grafana`_ 

.. _Download Grafana: http://docs.grafana.org/installation/mac/

Getting Started
---------------
.. code-block:: bash

    brew services start grafana

to check which services are running use:

.. code-block:: bash

    brew services list

Adding plugins
--------------

