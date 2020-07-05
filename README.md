# python-version-cheat-sheet
about the what and when of new python features

## overview

### python 3
- type annotations


### python 3.5
- **ATTENTION**: you cannot use type annotations for variables yet; instead use type comments


### python 3.6
- type annotations for variables
([PEP 526](https://www.python.org/dev/peps/pep-0526/))
- f-strings
([PEP 498](https://www.python.org/dev/peps/pep-0498/))


### python 3.7
- postponed evaluation of annotations via `from __future__ import annotations`
([PEP 563](https://www.python.org/dev/peps/pep-0563/))

- sort order of dicts is now guaranteed

- introduction of `breakpoint`, additionally to `import pdb;pdb.set_trace()`
([PEP 553](https://www.python.org/dev/peps/pep-0553/))


### python 3.8
- the walrus operator
([PEP 572](https://www.python.org/dev/peps/pep-0572/))


### python 3.9
- use `list` and `dict` for type annotations, instead of importing e.g. `from typing import List`


### python 3.10
- `from __future__ import annotations` is no longer necessary
([PEP 563](https://www.python.org/dev/peps/pep-0563/))



## official changelog

Do you need all the nitty gritty details?

- [official changelog](https://docs.python.org/3/whatsnew/changelog.html)


## contributing

Do you think this overview is useful? Share it!

Do you think you can contribute? Do not hesitate!

But let's keep it simple. This should not become a second changelog.
