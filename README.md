# AXOCTRL for Axoloti

This repo holds the (sub)patches for easily integrating Axoctrl board into Axoloti patches.


# Instructions

* Use the `format_flash_disk` to clear the flash disk of all existing files and data
* Upload the `startup_patch` patch as start up patch on the flash drive
* Create a new patch bank and include the all your patches with the `axoctrl` in them
* Then upload the index and the patches to the flash disk by first clicking the `Upload bank table` button and then the `Upload Patch Bank` button.


# Technical notes

The `startup_patch` is just a simple patch that will load the first patch from an uploaded patch bank.
