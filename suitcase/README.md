Suitcase uses
[native namespace packages](https://packaging.python.org/guides/packaging-namespace-packages/#native-namespace-packages).

This directory *must not* contain an ``__init__.py`` or it will break this
package and all other suitcase namespace packages.



# Changelog

## 0.1.3
Fixes:
- Fixed issue with empty data, this is now caught.
- can now save named tuples as they come from ophyd devices or camel's variable signal

## 0.1.2
Fixed issue with dots in paths

## 0.1.1
Added CAMELS plots to export function

## 0.1.0
Initial release
