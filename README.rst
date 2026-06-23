.. image:: logo/horizontal.svg
   :width: 480px
   :alt: websockets

.. note::

   This is a **YoCharge fork** of `python-websockets/websockets <https://github.com/python-websockets/websockets>`_.
   It extends the upstream library with EV charger-specific features: parsing the WebSocket request path
   to extract the charger ID, and enabling a debug mode for chargers listed in the ``DEBUG_CHARGERS``
   environment variable.

   Upstream documentation: https://websockets.readthedocs.io/


What else?
----------

This fork is maintained by `YoCharge <https://yocharge.com>`_. For changes
specific to this fork, please open an issue or pull request in the YoCharge
repository.

For issues with the upstream library, refer to the `original project
<https://github.com/python-websockets/websockets>`_.

Participants must uphold the `Contributor Covenant code of conduct`_.

.. _Contributor Covenant code of conduct: https://github.com/python-websockets/websockets/blob/main/CODE_OF_CONDUCT.md

``websockets`` is released under the `BSD license`_.

.. _BSD license: https://github.com/python-websockets/websockets/blob/main/LICENSE
