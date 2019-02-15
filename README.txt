===================
Odoo Sphinx Autodoc
===================

This package provides a sphinx extension that allows to use "openerp.addons.*" with sphinx autodoc feature.

Extentions
==========

Add odoo-sphinx-autodoc to your list of extentions

    extensions = [...
      "sphinxodooautodoc.ext.autodoc"
      ...]

Options
=======

- sphinxodoo_addons : List of addons name to load (if empty, no addon will be loaded)
- sphinxodoo_root_path : Path of the Odoo root directory
- sphinxodoo_addons_path : List of paths were Odoo addons to load are located
