conMT
=====

ConMT is a technically free open-source voxel game library with easy license skirting and game creation.

ConMT copyright (c) 2023 Victor BW <knodewaeee@gmail.com>

Minetest parent work copyright (C) 2010-2022 Perttu Ahola <celeron55@gmail.com> and contributors (see source file comments and the version control log)

Compiling
---------

<!-- - [Compiling on GNU/Linux](doc/compiling/linux.md) -->
- [Compiling on Windows](doc/compiling/windows.md)
<!-- - [Compiling on MacOS](doc/compiling/macos.md) -->

Docker
------
no

Version scheme
--------------
We use `major.minor.patch` as per future Vulkan compatibility that I'll never implement.

- Major is incremented when the release is a major redo (contains breaking changes), all other
numbers are set to 0.
- Minor is incremented when the release contains new non-breaking useful features,
patch is set to 0.
- Patch is incremented when the release only contains bugfixes, security patches, and very
minor/trivial features.
