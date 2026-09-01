# AM32 firmware

This is the upstream AM32 firmware checkout used by OpenESC. Work here only for
an explicitly requested AM32 firmware, target, or build task; board design and
40 A/channel or 60 A/channel product claims belong to the corresponding
OpenESC hardware repository and measured test evidence.

Preserve upstream style and build structure. Read `README.md` and `Makefile`,
inspect Git state, build only the requested MCU/target, and do not commit build
artifacts or infer a firmware task from hardware notes.
