wifineedle
==========

Sending Data Frames for Testing Purposes "Through Cooked Monitor Mode" over a wireless interface.
This is started with the requirement of sending an AMSDU packet for testing the AMSDU De-aggreagtion
in both AP and STA modes.But the same can be extended to send any test packets which the normal Wi-Fi
stack doesn't support yet.

This is mainly useful for sending packets while staying connected, if you want send packets while 
not connected then using the "libpcap" API is recommended.

For bugs/queries/contributions e-mail-to: chaitanya.mgit@gmail.com
==========
