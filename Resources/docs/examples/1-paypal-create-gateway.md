# 1. Paypal. Create Gateway. 

```php
<?php

use Payum\Paypal\ExpressCheckout\PaypalExpressCheckoutGatewayFactory;

$factory = new PaypalExpressCheckoutGatewayFactory();

$gateway = $factory->create(array(
    'username' => 'aUsername',
    'password' => 'aPassword',
    'signature' => 'aSignature',
    'sandbox' => true,
));
```
