# munifying-web

Experimental in-browser implementation of CVE-2019-13054/CVE-2019-13054 from Chrome 78+.

The page utilizes the new WebHID API to extract AES encryption keys from vulnerable dongles.

As this is a PoC, there is no proper error handling implemented. The code is supposed to
work with Logitech receivers utilizing a Texas Instruments Chip (R500, SPOTLIGHT, LightSpeed
Logitech Unifying with RQR24.x). The vulnerability was patched with firmware RQR24.10 / RQR24.11
for Logitech Unifying receivers.



For a full implemetation of a dumping/flashing tool for Unifying receivers, watch out for
[munifying](https://github.com/mame82/munifying)

## DISCLAIMER

**this code** is a Proof of Concept and should be used for authorized testing and/or 
educational purposes only. The only exception is using it against devices owned by yourself.

I take no responsibility for the abuse of this code or any information given in
the related documents. 

**I DO NOT GRANT PERMISSIONS TO USE this code TO BREAK THE LAW.**

I disclaim any warranty for this code, it is provided "as is".
