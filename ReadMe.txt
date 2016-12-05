# Installation

1. Copy the raiddump.c file to the grub-core/commands folder.
2. Add the following lines to the grub-core/Makefile.core.def file:

module = {
  name = raiddump;
  common = commands/raiddump.c;
};

3. Run the autogen.sh script to update necessary files.
4. Build.
