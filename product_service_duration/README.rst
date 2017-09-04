[![Build Status](https://travis-ci.org/zeroincombenze/product-attribute.svg?branch=10.0)](https://travis-ci.org/zeroincombenze/product-attribute)
[![license agpl](https://img.shields.io/badge/licence-AGPL--3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0.html)
[![Coverage Status](https://coveralls.io/repos/github/zeroincombenze/product-attribute/badge.svg?branch=10.0)](https://coveralls.io/github/zeroincombenze/product-attribute?branch=10.0)
[![codecov](https://codecov.io/gh/zeroincombenze/product-attribute/branch/10.0/graph/badge.svg)](https://codecov.io/gh/zeroincombenze/product-attribute/branch/10.0)
[![OCA_project](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-oca-10.svg)](https://github.com/OCA/product-attribute/tree/10.0)
[![Tech Doc](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-docs-10.svg)](http://wiki.zeroincombenze.org/en/Odoo/10.0/dev)
[![Help](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-help-10.svg)](http://wiki.zeroincombenze.org/en/Odoo/10.0/man/MM)
[![try it](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-try-it-10.svg)](http://erp10.zeroincombenze.it)


[![en](https://github.com/zeroincombenze/grymb/blob/master/flags/en_US.png)](https://www.facebook.com/groups/openerp.italia/)

.. image:: https://img.shields.io/badge/license-AGPL--3-blue.svg
================================================================
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3

Product Service Duration

Extension of products (services only) that allows them to be added to calendars.

As a note, if you add services with a `Minimum Time` (minimum time it
takes to complete that service) to an event, the meeting/event duration cannot
be less than the combined minimum time of those services.

For example, say your meeting involves two services, technical and design services.
If the technical service requires 2 hours and design requires 3 hours, then your
meeting must be at least 5 hours.

The above constraint does not apply on events that have `All Day` selected.

When changing the `Minimum Time` on services, this will not affect events that have
already ended.

Installation
------------


Configuration
-------------


Usage
-----

-----

=====

To use this module:

* Click the `Sales` tab in the top navigation, and go to `Settings`.
* Set `Product Variants` to `Products can have several attributes . . .`
* In the left panel, click on `Product Variants`.
* In the form view there, you'll see resources and minimum service times added.
* Calendar views also have products and minimum event durations added.

.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
   :alt: Try me on Runbot
   :target: https://runbot.odoo-community.org/runbot/135/10.0

Known Issues / Roadmap

Known issues / Roadmap
----------------------


Bug Tracker
-----------



Bugs are tracked on `GitHub Issues
<https://github.com/OCA/product-attribute/issues>`_. In case of trouble, please
check there if your issue has already been reported. If you spotted it first,
help us smash it by providing detailed and welcomed feedback.

Credits
-------



Images

* Odoo Community Association: `Icon <https://github.com/OCA/maintainer-tools/blob/master/template/module/static/description/icon.svg>`_.

[![Odoo Italia Associazione]]


### Contributors



* Brett Wood <bwood@laslabs.com>

### Funders

### Maintainer




.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

This module is maintained by the OCA.

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

To contribute to this module, please visit http://odoo-community.org.

[//]: # (copyright)

----

**Odoo** is a trademark of [Odoo S.A.](https://www.odoo.com/) (formerly OpenERP, formerly TinyERP)

**OCA**, or the [Odoo Community Association](http://odoo-community.org/), is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

**zeroincombenze®** is a trademark of [SHS-AV s.r.l.](http://www.shs-av.com/)
which distributes and promotes **Odoo** ready-to-use on its own cloud infrastructure.
[Zeroincombenze® distribution](http://wiki.zeroincombenze.org/en/Odoo)
is mainly designed for Italian law and markeplace.
Everytime, every Odoo DB and customized code can be deployed on local server too.

[//]: # (end copyright)

[//]: # (addons)

[//]: # (end addons)

[![chat with us](https://www.shs-av.com/wp-content/chat_with_us.gif)](https://tawk.to/85d4f6e06e68dd4e358797643fe5ee67540e408b)
