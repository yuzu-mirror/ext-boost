Boost libraries - trimmed down for Citra
========================================

This is a subset of Boost v1.57.0.

Currently imported libraries:
-----------------------------
* concept
* config
* container
* core
* intrusive
* iterator
* move
* mpl
* preprocessor
* range
* smart_ptr (`intrusive_ptr` only)
* type_traits
* utility

Additionally, all global boost headers are available, but not guaranteed to work unless their dependencies are included in any of the libraries mentioned above.
