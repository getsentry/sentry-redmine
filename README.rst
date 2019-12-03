sentry-redmine
==================

DEPRECATED: This project now lives in `sentry <https://github.com/getsentry/sentry/tree/master/src/sentry_plugins/redmine>`_

An extension for Sentry which integrates with Redmine. Specifically, it allows you to easily create
Redmine issues from events within Sentry.


Install
-------

Install the package via ``pip``::

    pip install git+git://github.com/getsentry/sentry-redmine@master

Configuration
-------------

Create a user within your Redmine install (a system agent). This user will
be creating tickets on your behalf via Sentry.

Go to your project's configuration page (Projects -> [Project]) and select the
Redmine tab. Enter the required credentials and click save changes.

You'll now see a new action on groups which allows quick creation of issues.
