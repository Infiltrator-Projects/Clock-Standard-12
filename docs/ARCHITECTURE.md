# Standard 12-Hour Clock — architecture

This module owns its unique clock formatting, timing and resource identity. Common 1.19.81 (a99ef676b0e43c7e645c81756e3fd38be0a54406) owns reusable arithmetic, civil timestamp conversion and the public provider ABI. The exact Common git submodule is compiled as its own archive and linked into the resource .so, rather than maintaining copied Common sources. The offline native installer embeds the pinned source, with regression and accuracy CI gates.
