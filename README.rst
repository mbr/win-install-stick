win-install-stick
=================

Shell script to create a bootable USB stick to install Windows from an .iso
file without another Windows machine.

Tested with Windows 7 (and an ISO-file from DreamSpark).


Example
-------

Assuming your usb stick is ``/dev/sdi``:

code-block:: sh

  sudo ./mkwinstick.sh /dev/sdi en_windows_7_professional_n_with_sp1_x64_dvd_u_677207.iso


Credit due
----------

* PZt at ``##windows`` on http://freenode.net
* https://serverfault.com/questions/6714/how-to-make-windows-7-usb-flash-install-media-from-linux#answer-167060
