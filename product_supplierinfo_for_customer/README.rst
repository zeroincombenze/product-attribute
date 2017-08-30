[![Build Status](https://travis-ci.org/zeroincombenze/product-attribute.svg?branch=8.0)](https://travis-ci.org/zeroincombenze/product-attribute)
[![license agpl](https://img.shields.io/badge/licence-AGPL--3-blue.svg)](http://www.gnu.org/licenses/agpl-3.0.html)
[![Coverage Status](https://coveralls.io/repos/github/zeroincombenze/product-attribute/badge.svg?branch=8.0)](https://coveralls.io/github/zeroincombenze/product-attribute?branch=8.0)
[![codecov](https://codecov.io/gh/zeroincombenze/product-attribute/branch/8.0/graph/badge.svg)](https://codecov.io/gh/zeroincombenze/product-attribute/branch/8.0)
[![OCA_project](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-oca-8.svg)](https://github.com/OCA/product-attribute/tree/8.0)
[![Tech Doc](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-docs-8.svg)](http://wiki.zeroincombenze.org/en/Odoo/8.0/dev)
[![Help](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-help-8.svg)](http://wiki.zeroincombenze.org/en/Odoo/8.0/man/MM)
[![try it](http://www.zeroincombenze.it/wp-content/uploads/ci-ct/prd/button-try-it-8.svg)](http://erp8.zeroincombenze.it)


[![en](http://www.shs-av.com/wp-content/en_US.png)](http://wiki.zeroincombenze.org/it/Odoo/7.0/man)

.. image:: https://img.shields.io/badge/licence-AGPL--3-blue.svg
================================================================
    :alt: License: AGPL-3
    :target: http://www.gnu.org/licenses/agpl-3.0.en.html

Use product supplier info also for customers

This modules allows to use supplier info structure, available in
*Procurements* tab of the product form, also for defining customer information,
allowing to define prices per customer and product.

Installation
------------

Configuration
-------------


For these prices to be used in sale prices calculations, you will have
to create a pricelist with a rule with option "Based on" with the value
"Supplier prices on the product form" (although the text is not clear enough).

Usage
-----

=====

There's a new section on *Sales* tab of the product form called "Customers",
where you can define records for customers with the same structure of the
suppliers.

.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
   :alt: Try me on Runbot
   :target: https://runbot.odoo-community.org/runbot/188/8.0


The product code / product name specified for the customer can be reflected
on the sale orders using module `product_supplierinfo_for_customer_sale
<https://github.com/OCA/product-attribute/tree/8.0/product_supplierinfo_for_customer_sale>`_

Known issues / Roadmap
----------------------


* Product prices through this method are only guaranteed on the standard sale
  order workflow. Other custom flows maybe don't reflect the price.
* The minimum quantity will not also be applied on sale orders.
* Computed fields in product.supplierinfo object won't properly work for
  customer type

Bug Tracker
-----------

Credits
-------


[![Odoo Italia Associazione]]

### Contributors

* Oihane Crucelaegui <oihanecrucelaegi@avanzosc.es>
* Pedro M. Baeza <pedro.baeza@serviciosbaeza.com>

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
