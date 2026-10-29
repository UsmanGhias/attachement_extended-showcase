# Attachment Extended: Preview-Only Documents

![Odoo](https://img.shields.io/badge/Odoo-17.0-714B67) ![Editions](https://img.shields.io/badge/Editions-Community%2C_Enterprise%2C_Odoo.sh-2563EB) ![License](https://img.shields.io/badge/License-LGPL--3-0F766E) [![Odoo App Store](https://img.shields.io/badge/Odoo_App_Store-Buy-875A7B)](https://apps.odoo.com/apps/modules/17.0/attachment_extended)

Some files should be visible to staff but not handed around, such as signed contracts or drawings. This app adds an Only Document Preview flag to attachments in the document module.

## What it does

- Only Document Preview checkbox on attachments
- Installs automatically alongside the document module it extends

## How to use it

1. Open an attachment in the document app and tick Only Document Preview.

## Technical notes

Technical name `attachment_extended`, Odoo 17.0.

Extends `ir.attachment` with one boolean field and a view. Depends on `bi_document` by BrowseInfo.

> Requires `bi_document` by BrowseInfo, which makes up most of the store price.

## Get the module

Buy it on the [Odoo App Store](https://apps.odoo.com/apps/modules/17.0/attachment_extended) for EUR 59, including the required document module. The purchase includes the full source code under the LGPL-3 licence.

Need it on another Odoo version, with changes for your workflow, or installed and tested on Odoo.sh? Email [iusmanghias@gmail.com](mailto:iusmanghias@gmail.com?subject=attachment_extended%20customisation) or see [CODCrafters](https://codcrafters.org).

---

This repository is the product page. The module source is private and comes with the licence.

Built by [Usman Ghias](https://usmanghias.co.uk), [CODCrafters](https://codcrafters.org).
