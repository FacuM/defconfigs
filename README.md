defconfigs
==========

Some custom kernel defconfigs made using menuconfig.

#### x86_64-legacygpu_defconfig

Required to add back support for legacy ATI Radeon HD and Intel devices.

#### Extra steps

- Place them in the following path:

   arch/x86/configs

- Type the next command:

   make x86_64-legacygpu_defconfig

- Build as normal.
