# Example StarterProject
A **starter project** to show how to set up and use automated testing in Python

Change package_name = example to your needs. The rest of the README just
serves as an example.

![Tests](https://github.com/tobibias/starter-project/actions/workflows/tests.yml/badge.svg)
![PyPi_Version](https://img.shields.io/pypi/v/lckr-jupyterlab-variableinspector)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

<p align="center">
<img src="https://user-images.githubusercontent.com/8370623/180626875-fe958128-6102-4f01-9ca4-e3a30c3148f9.png" width=100% height=100% 
class="center">
</p>

## Catalog
- [x] Code ... check
- [ ] TODO


## Results
### Example Table

|    name    | resolution | acc@1 | #params | FLOPs |     model     |
| :--------: | :--------: | :---: | :-----: | :---: | :-----------: |
| ConvNeXt-T |  224x224   | 82.1  |   28M   | 4.5G  | [model](TODO) |
| ConvNeXt-S |  224x224   | 83.1  |   50M   | 8.7G  | [model](TODO) |


## Installation

```
pip install example
```

## Development
Use the yapf auto-formatter to avoid arguing over formatting.

Install project in editable mode 
```
pip install -e .
```

1. Run plylint
2. Run mypy
3. Run tox


## License
This project is released under the MIT license. Please see the [LICENSE](LICENSE)
file for more information.

## Citation
If you find this repository helpful, please consider citing:
```
@Article{todo,
  author  = ...
}
```