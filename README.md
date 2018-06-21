RevTrax iFrame
==============
Displaying RevTrax Coupons on Your WebsIte

An iframe is a web page within a web page. When used you have complete control
over placement and contentsurrounding the iframe. This creates a branded user
experience with a printable coupon within the iframe. When printed, only the
coupon is printed. Pages inside the iframe are fully managed by RevTrax without
any work by clients.

Notes
-----
-   iFrame height is automatically sized, please do not specify height in your
    HTML or CSS.
-   Parameters are case sensitive: thisParameter is not the same as
    thisparameter
-   iFrame library is compatible with both secure (https://) and non-secure
    (http://) protocols
-   Parameters from client URL will automatically pass over to RevTrax\*,
    execution above will pass:
    -   utm_campaign=branded&utm_medium=search
-   Minimum iframe size: 350px width by 250px height.

Implemnentation
---------------
Implementing the RevTrax Iframe Library does not require any server side logic,
just (3) lines of JavaScript and HTML. Once implemented the library
automatically passes parameters from a client’s URL over to RevTrax

Code
----
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
<html><head><title>Sample RevTrax Iframe Code</title></head>
<body><p>RevTrax iFrame</p>

<script src="https://irxcm.com/RevTrax/js/rtxiframe.jsp?parent=mydiv&rtxuseqs=true&merchantId=19612173&programId=91494352&affiliateId=19612218&channel=brand"></script>

<div id="mydiv" style="width: 100%;" scrolling="no" allowtransparency="yes"></div>

<script>makeFrame();</script>

</body></html>
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Questions?
==========
Contact us: ProductTeam\@revtrax.com
