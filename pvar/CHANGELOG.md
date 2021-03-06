# Changelog for pvar

## 0.1.2.0

* Rename `modifyPVar` to `fetchModifyPVar` and `modifyPVarM` to `fetchModifyPVarM`. This
  is a breaking change in favor of consistency with other librarries.
* New implementation for `modifyPVar` and `modifyPVarM` that can return some artifact.
* Addition of `modifyFetchPVar` and `modifyFetchPVarM`
* Addition of `atomicModifyFetchIntPVar` and `atomicFetchModifyIntPVar`

## 0.1.1.0

* Addition of backwards compatible:
  * `isByteArrayPinned`, `isMutableByteArrayPinned` (that work on ghc-7.10 and ghc-8.0)
  * Primitive versions `isByteArrayPinned#`, `isMutableByteArrayPinned#`
* Support for GHC 7.10 and GHC 8.0
* Re-export `sizeOf` and `alignment` for easier compatibility with older primitive versions.


## 0.1.0.0

* Initial release
