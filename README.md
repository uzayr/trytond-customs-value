trytond-customs-value
=====================

This module adds a `customs value` field to Product Variants where the
customs value of a product can be recorded. Since most businesses have the
retail price (or list price) as the customs value, the default behavior is
to use the list price as the customs value.

Screenshots
-----------

To be uploaded

Why use this module
-------------------

This module was built to be a supporting module for the shipping modules
of Fulfil-io that integrates with carriers like FedEx, UPS and USPS. When
generating international shipment labels, the carriers expect customs
value to be electronically transferred to them.

Why not just use list price ?
-----------------------------

This works for most businesses. This is indeed the default behavior of
this module.

On the other hand, if you are wholesaler, you may not want
the retail list price being sent as the customs value for the product.
