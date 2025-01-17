==================================
Stock Production Lot Multi Company
==================================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:4becafacf9d8eea9adb8b52aa8c73b5f4af6260f7daf73f2967bde6b356ec3b7
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fmulti--company-lightgray.png?logo=github
    :target: https://github.com/OCA/multi-company/tree/12.0/stock_production_lot_multi_company
    :alt: OCA/multi-company
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/multi-company-12-0/multi-company-12-0-stock_production_lot_multi_company
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/multi-company&target_branch=12.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

This module was written to extend the functionality of serial numbers and make
them multi company aware.

This is especially important if you are using serial numbers as otherwise Odoo
may end up trying to merge stock.quant records having the same lot, but going
to the Customers location from 2 different companies (in case it was first
shipped from Company 1 to Company2) and this will fail due to a constraint.

**Table of contents**

.. contents::
   :local:

Configuration
=============

There is no specific configuration for this module.

Usage
=====

To use this module, you need to:

 * go to Inventory > Master Data > Lots / Serial Numbers to see the company_id in the tree and form views.
 * the usual multi company record rule is installed automatically.

Known issues / Roadmap
======================

* N/A

Changelog
=========

12.0.0.0.0 (2019-07-11)
~~~~~~~~~~~~~~~~~~~~~~~

* [MIG] migration to 12.0


Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/multi-company/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/multi-company/issues/new?body=module:%20stock_production_lot_multi_company%0Aversion:%2012.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* OdooMRP team
* AvanzOSC
* Serv. Tecnol. Avanzados - Pedro M. Baeza

Contributors
~~~~~~~~~~~~

* Marçal Isern <marsal.isern@qubiq.es>
* Ainara Galdona <ainaragaldona@avanzosc.es>
* Pedro M. Baeza <pedro.baeza@serviciosbaeza.com>
* Ana Juaristi <anajuarist@avanzosc.es>
* Lorenzo Battistini <lorenzo.battistini@agilebg.com>
* Simone Rubino <simone.rubino@agilebg.com>

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

This module is part of the `OCA/multi-company <https://github.com/OCA/multi-company/tree/12.0/stock_production_lot_multi_company>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
