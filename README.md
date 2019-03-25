Customized linux kernel for the thinkpad X1 tablet (gen 1 ) to prevent the following kernel message, that resulting in a broken kernel boot sometimes.

Kernel message:
`rmi4_f34 rmi4-00.fn34: rmi_f34v7_probe: Unrecognized bootloader version`

To prevent this kernel message I deactivated the option `CONFIG_RMI4_F34`.
