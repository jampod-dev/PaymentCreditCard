PaymentCreditCard
=================

A generic credit card payment method for ProcessWire Shop. In keeping with ProcessWire's philosophy, it generates minimal markup and styling so you can easily adapt the payment form to your site's design.

###Use:

* Install the module.
* At line 200 of PaymentCreditCard.module, pass the credit card data array and total amount into the function or API call provided by your payment processor. Put the result into the $result variable.
* Modify the form and credit card data array if needed to fit your payment processor's requirements.
