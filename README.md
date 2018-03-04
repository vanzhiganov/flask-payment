# Flask Payment

Beginning to build a Flask Extension which takes the pain out of calling Payment
Gateways such as Paypal, Google Checkout etc.

Implemented in a 'Flaskified' application and persistance agnostic way.

Takes some inputs, calls web services, and returns some outputs -
such as success/reason for failure/subscription period/etc.

Responsibility devolved to the application for persistance of all data, 
Flask Payment will not store anything itself.

To start with Paypal.

To later support Google Checkout.

To generalise to other Payment gateways over time.
