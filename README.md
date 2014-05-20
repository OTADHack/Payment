Payment API
=========

Applications use the RESTful Payment interface to charge an amount to an end-user's account using Diameter, refund amounts to that account, and split charge amounts among multiple end-users. Applications can also reserve amounts, reserve additional amounts, charge against the reservation or release the reservation.

Version
----

5.1

Usage
----

Follow this steps:

+ Request your credentials on the [Oracle's TADHack website](http://tadhack.optaresolutions.com).
+ Download the source code:

```sh
git clone https://github.com/OTADHack/Payment.git
cd Payment
```
+ In [SoapUI 5.0 or above](http://www.soapui.org/), go to File -> Import project and choose the file Payment/SoapUI/API-Payment-soapui-project.xml
+ Double click on Request 1 of the Service http://ocsg.optaresolutions.com:8001
+ In the Request Properties box, change Username and Password with the credentials requested in the firs step.
+ Click on the green arrow of the Request 1 window.
+ Done! Your first charge is done!

Documentation
----

All the documentation can be found in the [Oracle's TADHack website](http://tadhack.optaresolutions.com/?page_id=102).

A summarize of the API can be found [here](http://ocsg.optaresolutions.com:8001/rest/payment/index.html).


Support
----

If you have any doubt, ask it in [the Issues section](https://github.com/OTADHack/Payment/issues).

License
----

Copyright © 2007, 2013, Oracle and/or its affiliates. All rights reserved. Usage only allowed for TADHack Developers.
