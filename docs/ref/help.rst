help
====

.. http:get:: /api/3.0/help

	Retrieve a list of API endpoints.

Public API
----------
If the Public API is enabled, unauthenticated users can make requests to the */help* endpoint. Both the public and authenticated responses are identical.

.. literalinclude:: ../examples/response/help.json
	:language: json
	:linenos:
