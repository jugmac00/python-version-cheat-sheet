# python-version-cheat-sheet
about the what and when of new python features

## overview

### python 3.0
- introduction of **extended iterable unpacking** which enables e.g. `a, *b, c = [1, 2, 3, 4, 5]` so `b` becomes `[2, 3, 4]`
([PEP 3132](https://www.python.org/dev/peps/pep-3132/))

### python 3.3
- introduction of **yield from**
([PEP380](https://peps.python.org/pep-0380/))

### python 3.4
- introduction of **pathlib**
([PEP 428](https://www.python.org/dev/peps/pep-0428/))

### python 3.5
- introduction of **type annotations**
([PEP 484](https://www.python.org/dev/peps/pep-0484/))
- **ATTENTION**: you cannot use **type annotations** for variables yet; instead use type comments
- introduction of **additional unpacking generalizations**
([PEP 448](https://peps.python.org/pep-0448/))

### python 3.6
- introduction of **type annotations** for variables
([PEP 526](https://www.python.org/dev/peps/pep-0526/))
- **f-strings**
([PEP 498](https://www.python.org/dev/peps/pep-0498/))
- introduction of **underscores in numeric literals**, e.g. `1_000`
([PEP 515](https://www.python.org/dev/peps/pep-0515/))

### python 3.7
- **postponed evaluation of annotations** via `from __future__ import annotations`
([PEP 563](https://www.python.org/dev/peps/pep-0563/))
- **sort order of dicts** is now guaranteed
- introduction of  `breakpoint()`, additionally to `import pdb;pdb.set_trace()`
([PEP 553](https://www.python.org/dev/peps/pep-0553/))
- introduction of **data classes**
([PEP 557](https://www.python.org/dev/peps/pep-0557/))

### python 3.8
- introduction of the **walrus operator**
([PEP 572](https://www.python.org/dev/peps/pep-0572/))

### python 3.9
- **builtin generic types**, that means you can use `list` and `dict` for type annotations, instead of importing e.g. `from typing import List`
([PEP 585](https://www.python.org/dev/peps/pep-0585/))

### python 3.10
- allow writing union types as X | Y
([PEP 604](https://www.python.org/dev/peps/pep-0604/))
- introduction of **structural pattern matching**, which is a kind of switch/case on steroids
([PEP 622](https://www.python.org/dev/peps/pep-0622/))

### python 3.11
- **exception groups and except\***, a new standard to raise and handle multiple unrelated exceptions simultaneously
([PEP654](https://peps.python.org/pep-0654/))
- support for parsing TOML in the standard library via **tomllib**
([PEP 680](https://peps.python.org/pep-0680/))

## official changelog

Do you need all the nitty gritty details?

- [official changelog](https://docs.python.org/3/whatsnew/changelog.html)


## contributing

Do you think this overview is useful? Share it!

Do you think you can contribute? Do not hesitate!

But let's keep it simple. This should not become a second changelog.
