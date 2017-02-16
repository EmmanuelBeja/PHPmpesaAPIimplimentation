# PHPmpesaAPIimplimentation
This is a basic mpesa API implimentation with a form for inputing a few details.It adds a package smodav/mpesa from packagist.
Check out vendor/smodav/mpesa/README.md to get a description on configuring  and using Smodav/Mpesa.
You can as well check out the package on github at 'Smodav/Mpesa'.
In this case change the line bellow in vendor/smodav/mpesa/config/mpesa to a url directing to index.php.

'callback_url' => "http://payments.smodavproductions.com/checkout.php",

This implimentation requires a FQDN to be fully functional.
This implimentation basically extends Smodav/Mpesa implimentation making it easier to comprehend.

Happy coding!!
