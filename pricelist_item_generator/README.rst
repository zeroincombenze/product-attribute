[![Build Status](https://travis-ci.org/zeroincombenze/product-attribute.svg?branch=8.0)](https://travis-ci.org/zeroincombenze/product-attribute)
[![license agpl](https://img.shields.io/badge/licence-AGPL--3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0.html)
[![Coverage Status](https://coveralls.io/repos/github/zeroincombenze/product-attribute/badge.svg?branch=8.0)](https://coveralls.io/github/zeroincombenze/product-attribute?branch=8.0)
[![codecov](https://codecov.io/gh/zeroincombenze/product-attribute/branch/8.0/graph/badge.svg)](https://codecov.io/gh/zeroincombenze/product-attribute/branch/8.0)
[![OCA_project](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-oca-8.svg)](https://github.com/OCA/product-attribute/tree/8.0)
[![Tech Doc](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-docs-8.svg)](http://wiki.zeroincombenze.org/en/Odoo/8.0/dev)
[![Help](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-help-8.svg)](http://wiki.zeroincombenze.org/en/Odoo/8.0/man/MM)
[![try it](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-try-it-8.svg)](http://erp8.zeroincombenze.it)


[![en](https://github.com/zeroincombenze/grymb/blob/master/flags/en_US.png)](https://www.facebook.com/groups/openerp.italia/)

.. image:: https://img.shields.io/badge/licence-AGPL--3-blue.svg
================================================================
   :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
   :alt: License: AGPL-3

Pricelist Item Generator
========================

This module allows to create pricelist items in a bulk way,
by separate price elements and products informations. 

It avoids a lot of manual entries.


Installation
------------




Configuration
-------------





To configure this module (for non admin user), you need to:

#. Go to Settings > Configuration > Sales > Quotation and Sales > Customer Features
#. Check 'Use pricelists'

Usage
-----

-----

-----

-----

-----

-----

-----

=====

To use this module, you need to:

* Go to Sales > Configuration > Pricelists > Price Items Generator.
* Create a new one filling required fields and activate it.
* Create a price item rule in 'Price items' part.
* Add 2 rows in 'Involved products'
  (i.e. one with a product and one with a category).

.. figure:: pricelist_item_generator/static/description/img1.png
   :alt: completed generator
   :width: 600 px

* Save and click on 'Synchonize with Pricelist' button.
* Click on the version link: you now see a screen like this.

.. figure:: pricelist_item_generator/static/description/img2.png
   :alt: standard pricelist populated by generator
   :width: 600 px

* It's the standard Pricelist Version screen improved by cutting rules 
  in 2 parts: the standard one (Manual rules) and the automatic created 
  by this module.

* If you want duplicate generators, you may also duplicate one2many parts
  as here 'Price items'.

.. figure:: pricelist_item_generator/static/description/img3.png
   :alt: duplicate settings on price item generator
   :width: 600 px

.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
   :alt: Try me on Runbot
   :target: https://runbot.odoo-community.org/runbot/135/8.0


Known issues / Roadmap
----------------------





* Only support sales pricelist: others possible

Bug Tracker
-----------





Bugs are tracked on `GitHub Issues
<https://github.com/OCA/product-attribute/issues>`_. In case of trouble, please
check there if your issue has already been reported. If you spotted it first,
help us smashing it by providing a detailed and welcomed feedback.

Credits
-------





Images

* Icon images comes from https://icons8.com/web-app/for/all/price%20dollar






### Contributors





* David BEAL <david.beal@akretion.com>

### Funders
### Maintainer









.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

This module is maintained by the OCA.

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

To contribute to this module, please visit https://odoo-community.org.

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
