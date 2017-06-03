this tree i a fork of https://github.com/tobiasjakobi/linux-odroid-public.git

as tobias does not seem to update it any longer, i plan to keep it up to date to the latest 4.9 lts kernel

besides that it contains some extras:

* a aptch which makes reboot working again on at least odroid x2 and u3
* a patch to set the eth mac address on the kernel cmd line (smsc95xx.macaddr=11:22:33:44:55:66)
* a config containing all kernel options required to run docker
