# pas-vmp-glueimport

It's a simple project to add imports recovered by VMSweeper tool (by Vamit) to VMProtect dump file.
Tested to compile with Delphi XE8.

As you can see from the sources, it parses reference file generated by VMSweeper, extracts import infos and generates new import table for dump file (uses pe-image-for-delphi project).

It's not guaranteed to work on any file.

This repository was created in case it will be helpful.
It's not going to be updated.
