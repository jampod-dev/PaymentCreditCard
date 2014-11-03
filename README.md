PaymentCreditCard
=================

A generic credit card payment method for ProcessWire Shop. 

###Use:

* Install the module.
* At line 200 of PaymentCreditCard.module, add the function provided by your payment processor for processing credit card numbers. Put the result of that function into the $result variable.
* Modify the form and credit card data array if needed to fit your payment processor's requirements.
