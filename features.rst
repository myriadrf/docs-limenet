Features and Specifications
===========================

SDR card
--------

.. figure:: images/LimeNET_SDR_Card_1.png

Software Defined Radio (SDR) with integrated front end – LimeNET is built on
LimeSDR software-defined radio technology to deliver an app-enabled network
solution covering any standard from IoT to 5G. Use of Lime’s SDR platform
provides the most flexible radio hardware solution that enables numerous
applications from IoT to 5G and small-cell configurations and services. It could
be used to create on-demand network solutions where services could be easily
offered for any Telco centric services. LimeNET comes pre-equipped with a
flexible front-end module that provides filtering and amplification.

.. table:: Table 1: LimeSDR Features and Specifications.

   +---------------------------+------------------------------------------------------------------------------------------+
   |RF Chipset                 |3x Lime Microsystems `LMS7002M FPRF`_                                                     |
   +---------------------------+------------------------------------------------------------------------------------------+
   |RF LO frequency\ :sup:`1`  |30MHz – 3.8GHz                                                                            |
   +---------------------------+------------------------------------------------------------------------------------------+
   |RF channels                |2x2 MIMO for 5G, 2x2 MIMO for 4G, 2x RX for spectrum monitoring and 2x TX for calibrations|
   +---------------------------+------------------------------------------------------------------------------------------+
   |RF bandwidth               |4G: up to 40MHz                                                                           |
   +                           +------------------------------------------------------------------------------------------+
   |                           |5G: up to 100MHz                                                                          |
   +---------------------------+------------------------------------------------------------------------------------------+
   |Default                    |4G: B1, B3, B7 or B28                                                                     |
   +                           +------------------------------------------------------------------------------------------+
   |supported bands\ :sup:`2`  |5G: n48, n78\ :sup:`3`                                                                    |
   +---------------------------+------------------------------------------------------------------------------------------+
   |FPGA family                |Xilinx Artix7, `XC7A200T`_                                                                |
   +---------------------------+------------------------------------------------------------------------------------------+
   |PCIe generation            |Gen 2, x4, 2000MB/s                                                                       |
   +---------------------------+------------------------------------------------------------------------------------------+
   |Clock oscillator           |VCOCXO, VCTCXO, `CDCM6208`_                                                               |
   +---------------------------+------------------------------------------------------------------------------------------+
   |Location services          |Galileo, Glonass, GPS, Beidu                                                              |
   +---------------------------+------------------------------------------------------------------------------------------+

.. note::

   * :sup:`1`\ Continous coverage.
   * :sup:`2`\ Other bands possible by request.
   * :sup:`3`\ Subset of 3.4-3.6GHz supported by default.

x86 system
----------

.. table:: Table 2: Typical LimeNET x86 System Features and Specifications.

   +----------------------+-----------------------------------------------------------------------------------------------+
   |CPU\ :sup:`1,2`       |`AMD, Ryzen 7 5700G, 8C/16T`_ or `Ryzen 9 5900X, 12C/24T, 4.60GHz`_                            |
   +----------------------+-----------------------------------------------------------------------------------------------+
   |Motherboard\ :sup:`1` |`GIGABYTE, X570 AORUS PRO, AT`_                                                                |
   +----------------------+-----------------------------------------------------------------------------------------------+
   |RAM\ :sup:`2`         |16GB, DDR4, 3600MHz (up to 128GB)                                                              |
   +----------------------+-----------------------------------------------------------------------------------------------+
   |Storage\ :sup:`1,2`   |500GB SATA SSD                                                                                 |
   +----------------------+-----------------------------------------------------------------------------------------------+
   |Cooling\ :sup:`1`     |Liquid/air combination                                                                         |
   +----------------------+-----------------------------------------------------------------------------------------------+
   |x86 subsystem case    |4U rackmount server chassis                                                                    |
   +----------------------+-----------------------------------------------------------------------------------------------+
   |LimeNET system case   |Indoor, IP20, Rack type, 7U size, 60x45x40cm (WxLxH). Houses all hardware parts except Antenna.|
   +----------------------+-----------------------------------------------------------------------------------------------+

.. note::

   * :sup:`1`\ Vendor may vary.                
   * :sup:`2`\ Specification may be customised.

RF Front-End
------------





4G/5G backhaul
--------------





Software
--------




.. _LMS7002M FPRF: https://limemicro.com/technology/lms7002m/
.. _XC7A200T: https://www.xilinx.com/products/silicon-devices/fpga/artix-7.html#productTable
.. _CDCM6208: https://www.ti.com/product/CDCM6208
.. _AMD, Ryzen 7 5700G, 8C/16T: https://www.amd.com/en/products/apu/amd-ryzen-7-5700g
.. _Ryzen 9 5900X, 12C/24T, 4.60GHz: https://www.amd.com/en/products/cpu/amd-ryzen-9-5900x 
.. _GIGABYTE, X570 AORUS PRO, AT: https://www.gigabyte.com/Motherboard/X570-AORUS-PRO-rev-11-12
