0.4.0 2019-08-30
----------------

* Bugfix ensure the response timeout has a default.
* Support Quart >= 0.10.0

0.3.0 2019-04-22
----------------

* Fixed import of RequestTimeout from quart.
* Upgrade to ASGI 3.0 (Lifespan spec 2.0).
* Bugfix prevent MultiErrors from crahsing the app.
* Add py.typed for PEP 561 compliance.
* Handle individual exceptions in MultiErrors.

0.2.0 2019-01-29
----------------

* Use the latest Hypercorn and Quart run definition.
* Allow for background tasks to be started, the app now has a nursery
  for background tasks.
* Support Quart >= 0.8.0.
* Support serving static files.

0.1.0 2018-12-17
----------------

* Released initial alpha version.
