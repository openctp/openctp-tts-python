# openctp-tts-CTP_VERSION

[![PyPI - Python Version](https://badgen.net/badge/python/3.7|3.8|3.9|3.10|3.11/blue)](https://pypi.org/project/openctp-tts-CTP_VERSION)

-----

**Table of Contents**

- [Installation](#installation)
- [License](#license)

## Installation

```console
pip install openctp-tts-CTP_VERSION
```

## Example

[Demo](https://github.com/Jedore/openctp-tts-python/tree/main/demo)

```python
from openctp_tts_CTP_VERSION import mdapi, tdapi

md_api = mdapi.CThostFtdcMdApi.CreateFtdcMdApi("market")
td_api = tdapi.CThostFtdcTraderApi.CreateFtdcTraderApi('user_id')
```

## License

`openctp-tts-CTP_VERSION` is distributed under the terms of the [MIT](https://spdx.org/licenses/MIT.html) license.
