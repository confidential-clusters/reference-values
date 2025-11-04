# Reference values

This repository will store files that will act as reference values to
calculate the expected PCR values.

# Repository hierarchy

## Efivars

The `efivars` directory contains a sub-directory per platform. For
example, qemu-kvm. Under that, it could contain platform variations,
such as the version.

For example, qemu-kvm contains the `fedora-42`, `rhel-9.6`...
subdirectories, one per host OS version we are dealing with.

## Mok variables

The subdirectories under `mok-variables` contain the guest OS version as
the identifier. It has nothing to do with the host OS version as in the
case of efivars for the qemu-kvm platform.
