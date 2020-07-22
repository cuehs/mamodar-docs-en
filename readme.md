# MaMoDaR - English documentation

The project „MaMoDaR: Management Molekularer Daten im Research Data Life Cycle“ wants to optimize the efficient and sustainable handling of reasearch data. A userfriendly software solution is developing which is called DataLinker. The DataLinker supports the structred publilcation of reasearch data according to the FAIR principles. The DataLinker includes already existing solutions like the Research Data Management Organiser (RDMO) and public repositories as GenBank.

## Setup

First install `sphinx`, `sphinx-autobuild`, and `sphinx_rtd_theme`:

.. code:: bash

    pip install -r requirements.txt

Then, the HTML files can be created using:

.. code:: bash

    make html

A live server, which auto-updates itself after a file is saved, can be started using:

.. code:: bash

    make live

The documentation is then available on http://localhost:8000.
