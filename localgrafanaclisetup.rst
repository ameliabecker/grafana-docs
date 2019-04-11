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

Getting Started
---------------
Start the service and open the influx shell

.. code-block:: bash

    $service influxdb start
    $influx
    >

Using sample data:

`instructions`_ 

.. _instructions: https://docs.influxdata.com/influxdb/v1.7/query_language/data_download/


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

.. code-block:: bash

    grafana-cli plugins install grafana-piechart-panel


Fun Settings in Grafana
-----------------------

* setting the "relative time" changes the time range for that single graph
* 
* 