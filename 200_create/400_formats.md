# Knowing appliance formats

SUSE Studio can create appliances in several formats which are used for
different purposes:

## Live CD/DVD (.iso)

Use the Live CD/DVD, if you want to try out your appliance without installing
it. This is useful for testing and debugging or if you do not have a spare hard
disk available at the moment.

## OVF Virtual machine

Use the OVF format, if you need to exchange appliances in different virtual
machines like VirtualBox, VMware ESX servers, and others. The Open
Virtualization Format (OVF) is an open standard to distribute and package
virtual appliances. It requires the ovftool from VMware. Due to licensing issues
we cannot distribute the tools with SUSE Studio at the moment. Download, install
and set up the tools from http://communities.vmware.com/community/developer/ovf.
This option is disabled by default.

## Preload ISO (.iso)

Use the preload ISO, if you want to boot from CD/DVD and dump it to your hard
disk without knowing too much about the details of the dump procedure. A preload
ISO is an image wrapped as a bootable CD/DVD. After you have booted, it offers
to overwrite your hard disk. If you select Yes, the image will be dumped to your
hard disk.

## USB stick/hard disk image

Use this format, if you need a convenient method to boot from a USB stick or you
want to manually control the dump process. You need some knowledge about the dd
command.

## VMware / VirtualBox / KVM (.vmdk)

Use the VMDK format, if you want to start your appliance in a virtual machine
like VMware® or VirtualBox®. It is similar to the OVF format. This is another
method to test an appliance without formatting any hard disk.

## XEN guest

Use this format, if you want to run your appliance in a Xen hypervisor. This is
mainly useful for experts and is not covered in this manual. See
http://www.novell.com/documentation/sles11/book_xen/data/book_xen.html for
additional information.