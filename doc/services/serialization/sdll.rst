.. _sdll_reference:

Simple Data Link Layer (SimpleDLL)
##############################

SimpleDLL is a data serialization library based on the HDLC (High-Level Data Link
Control) protocol that provides a simple and low-footprint mechanism to
synchronize data frames between two or more devices.

Unlike HDLC, SimpleDLL only ensures that the frame is transported correctly and
provides a prototype function to give the user the option to select the
verification procedure (i.e: CRC-16, CRC-32, CHKSUM, etc.).
