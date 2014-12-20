kernel_so_timestamp
===================

Example code for kernel SO_TIMESTAMP feature

Contains
========
ku-latency and send_data are a pair. They provide a sample code to view how
SO_TIMESTAMP provides receive timestamp.

main provide a way to see how to get send timestamp.

Things to check for SO_TIMESTAMP
===============================
  Check ethtool to see if the NIC provide hardware timestamp.
  Use kernel 3.16.0. Lesser then 3.2 do not have the feature.

