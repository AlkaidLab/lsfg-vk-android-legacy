# pe-parse library snapshot

This directory contains the `pe-parser-library` portion of `pe-parse`, copied
from commit `31ac5966503689d5693cd9fb520bd525a871e17`.

Only the parser library sources required by `lsfg-vk-android` are vendored
here. The upstream examples, tests, Python bindings, and Corkami PE test
corpus are intentionally excluded. The test corpus is not part of the Android
frame-generation build and may contain executable proof-of-concept files that
are flagged by local antivirus software.

The source remains under the original MIT license. See `LICENSE` and the
license notices retained in the source files.
