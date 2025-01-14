================
 Error Messages
================

Here list all the errors when running :command:`pyarmor` or obfuscated scripts.

If something is wrong, search error message here to find the reason.

If no exact error message found, most likely it's not caused by Pyarmor, search
it in google or any other search engine to find the solution.

For example, someone reports error ``Operation did not complete successfully
because the file contains a virus or is potentially unwanted software question``

It's caused by Windows Defender, not Pyarmor. I'm sure Pyarmor is safe, but it
uses some technics which let anti-virtus tools makes wrong decision.

In most of case, the outer error is out of my control, for this example, the
solutions what I thought of

1. Check documentation of Windows Defender
2. Ask question in MSDN
3. Google this error message


Building Errors
===============

Here list all the errors when run :command:`pyarmor` in building machine

* out of license

  Using any feature is not avaiable in trial version or current Pyarmor License.

  Refer to :doc:`../licenses`

* not machine id

  This machine is not registered, or the hardware information is changed.

  Try to register Pyarmor again to fix it.

* query machine id failed

  Pyarmor need query harddisk serial number or mac address, if it could not get
  hardware information, it complains of this.

* unknown license type OLD

  You purchase old license for Pyarmor 7.x, here are :doc:`the latest licenses
  <../licenses>`

  If you prefer to use Pyarmor 7.x, please use ``pyarmor-7`` or downgrade
  pyarmor to 7.7.4

  If you prefer to use Pyarmor 8.0+, please refund this order if it's still not
  activated:
    - Email to Ordersupport@mycommerce.com with order information and ask for
      refund.
    - Or click FindMyOrder page to submit refund request

Runtime Errors
==============

Here list all the errors when run the obfuscated scripts

* error code out of range

* this license key is expired

* this license key is not for this machine

* missing license key to run the script

* unauthorized use of script

* this Python version is not supported

* the script doesn't work in this system

* the format of obfuscated script is incorrect

  may caused by

  - the obfuscated script is made by other Pyarmor version
  - can not get the path of runtime package

* the format of obfuscated function is incorrect

.. include:: ../_common_definitions.txt
