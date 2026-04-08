# core logger engine

> A robust and decoupled logging abstraction layer for Python, built with the Hexagonal pattern.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Version](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/Rick-torrellas/core-log-engine/badges/version.json)
[![CI CD](https://github.com/Rick-torrellas/core-log-engine/actions/workflows/main.yaml/badge.svg)](https://github.com/Rick-torrellas/core-log-engine/actions/workflows/main.yaml)
[![Python Version](https://img.shields.io/badge/python-3.11+-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Download](https://img.shields.io/github/v/release/Rick-torrellas/core-log-engine?label=Download&color=orange)](https://github.com/Rick-torrellas/core-log-engine/releases)
[![Ask DeepWiki](https://img.shields.io/badge/DeepWiki-Documentation-blue?logo=gitbook&logoColor=white)](https://deepwiki.com/Rick-torrellas/core-log-engine)

---

## 📖 Description

A simple and robust abstraction layer for the Python logging system, built following the Ports and Adapters (Hexagonal) pattern. This design allows you to decouple your application from the concrete logging implementation, facilitating testing, maintenance, and the ability to switch logging libraries in the future without modifying your core domain code.

---

## Installation

```bash
pip install capsulecore_logger
```


## Usage

```python
from CapsuleCore_logger import ConsoleLogger

logger = ConsoleLogger()

logger.info("This is an informational message.")
logger.debug("This is a debug message.")
logger.warning("This is a warning message.")
logger.error("This is an error message.")
```

---



## 📄 License

Distributed under the MIT License. See the LICENSE file for more information.

