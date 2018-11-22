# fs-extra: Optimisations and extensions to std:fs.

This library offers extensions to the functionality in `std::fs`.

Currently this consists of the following:

* A drop-in replacement for `std::fs::copy()` that supports sparse files and
  `copy_file_range()` on Linux.

