*********************
Using Grafana Locally
*********************
On launch
=========
.. code-block:: bash

    $ brew services list
    $ brew services start influxdb
    $ brew services start grafana

in browser, navigate to `localhost port 3000 <http://localhost:3000/>`_

default: `admin` and `admin`

On shutdown
===========
.. code-block:: bash

    $ brew services list
    $ brew services stop influxdb
    $ brew services stop grafana