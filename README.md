# Daikin Airconditioner/Air source heat pump data/control through Wi-Fi API

[![Python package](https://github.com/arska/python-daikinapi/actions/workflows/main.yml/badge.svg)](https://github.com/arska/python-daikinapi/actions/workflows/main.yml)
[![PyPI version](https://badge.fury.io/py/daikinapi.svg)](https://badge.fury.io/py/daikinapi)

## Compatibility

Testing with Daikin BRP051A41 Wi-Fi Interface
## Usage

see example.py for runnable example

```python
from daikinapi import Daikin

API = Daikin("192.168.1.3")
print(API)
print(API.target_temperature)
```

produces:
```
Daikin(host=192.168.1.3,name=mydevice,mac=D0C5D304A0B1)
21.0
```

