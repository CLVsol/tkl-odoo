Odoo (formerly OpenERP) - Open Source Apps To Grow Your Business.
=================================================================

`_Odoo`_ is a suite of web based open source business apps.

It's main apps include an <a href="https://www.odoo.com/page/crm">Open Source CRM</a>, <a href="https://www.odoo.com/page/website-builder">Website Builder</a>, <a href="https://www.odoo.com/page/e-commerce">eCommerce</a>, <a href="https://www.odoo.com/page/project-management">Project Management</a>, <a href="https://www.odoo.com/page/accounting">Billing & Accounting</a>, <a href="https://www.odoo.com/page/point-of-sale">Point of Sale</a>, <a href="https://www.odoo.com/page/employees">Human Resources</a>, Marketing, Manufacturing, Purchase Management, ...  Each application is standalone but you get a full featured <a href="https://www.odoo.com">Open Source ERP</a> if you install several apps as they integrate to each others.


This appliance is based on `LAPP stack`_, presenting the features:

- SSL support out of the box.
- PHP, Python and Perl support for Apache2 and PostgreSQL.
- `PHPPgAdmin`_ administration frontend for PostgreSQL (listening on
  port 12322 - uses SSL).
- Webmin modules for configuring Apache2, PHP and PostgreSQL.
- PostgreSQL listening on localhost (security)
- PostgreSQL password encryption enabled by default (security).
- The *postgres* user is trusted when connecting over local unix sockets
  (convenience).

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH: username **root**
-  PostgreSQL, phpPgAdmin: username **postgres**

.. _Odoo: http://www.turnkeylinux.org/lapp
.. _LAPP stack: http://www.turnkeylinux.org/lapp
.. _PHPPgAdmin: http://phppgadmin.sourceforge.net/
