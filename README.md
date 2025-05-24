# Rexterminatoromega

## Security is an illusion

[![N|Solid](https://www.python.org/static/img/python-logo.png)](https://www.python.org/)

Tool focused on cyber attacks, fully developed in python.

> Disclaimer: This tool is provided for educational and testing purposes only. The authors are not responsible for any misuse or illegal activities performed using this software.
---
## Summary

- [About](#about)
- [Libraries](#libraries)
- [Installation](#installation)
- [Versions](#versions)
- [Usage](#usage)
- [License](#license)


---
##  About

**Rexterminatoromega** is a hybrid system combining scraping, machine learning, and asynchronous automations to perform data scanning, classification, and analysis.  
Built with a focus on **efficiency**, **flexibility**, and **extensibility**.

> No system is truly secure. Use responsibly.
---

## Libraries

Rexterminatoromega uses a number of open source Python libraries and tools to work properly:

- **[requests]** – HTTP library for humans  
- **[subprocess]** – Spawns new processes, connects to their input/output/error pipes  
- **[threading]**, **[asyncio]**, **[multiprocessing]** – Built-in concurrency and parallelism  
- **[time]**, **[random]**, **[string]**, **[re]**, **[sys]**, **[os]**, **[platform]** – Core Python modules for utilities and system interactions  
- **[base64]**, **[json]**, **[argparse]**, **[functools]** – Data encoding, parsing, and command-line interfaces  
- **[xml.etree.ElementTree]** – Simple and efficient XML processing  
- **[urllib.parse]** – URL parsing and joining utilities  
- **[pandas]** – Powerful data structures for data analysis  
- **[numpy]** – Fundamental package for numerical computing  
- **[BeautifulSoup]** – HTML/XML parsing made easy  
- **[scrapy]** – Web crawling framework for large-scale scraping  
- **[scikit-learn]** *(sklearn)* – Machine learning library with models and evaluation tools  
- **[torch]** – Deep learning framework (PyTorch)  
- **[flask]** – Lightweight web application framework  
- **[aiohttp]** – Asynchronous HTTP client/server  
- **[boto3]** – AWS SDK for Python  
- **[cryptography]** – Secure encryption and key management  
- **[sqlite3]** – Lightweight disk-based database  
- **[logging]** – Flexible logging system  
- **[pkg_resources]** – Resource access and package management  

## Installation

Rexterminatoromega requires [Python](https://www.python.org/) v3.13.3+ to run.

Install the dependencies

```bash
pip install -r requirements.txt
```
---
### ️ Nmap

1. Download Nmap from the official site:  
   [https://nmap.org/download.html](https://nmap.org/download.html)

2. Install it using the installer.

3. After installation, **copy the `nmap.exe` file** from the installation directory  
   (usually `C:\Program Files (x86)\Nmap`) to:  
---
### SQLMap

1. Clone the SQLMap repository:  
```bash
git clone https://github.com/sqlmapproject/sqlmap.git
```
2. Move the cloned folder into the project directory as:
```bash
tools/sqlmap/
```
3. The final path should look like:
```bash
tools/sqlmap/sqlmap.py
```
---
## Versions

The Tool was developed based on the following versions:

| LIBRARY         | VERSION  |
|----------------|----------|
| requests        | 2.31.0   |
| beautifulsoup4  | 4.12.3   |
| scrapy          | 2.11.2   |
| scikit-learn    | 1.5.1    |
| pandas          | 2.2.2    |
| numpy           | 1.26.4   |
| torch           | 2.3.1    |
| flask           | 3.0.3    |
| boto3           | 1.34.149 |
| cryptography    | 42.0.8   |
| aiohttp         | 3.9.5    |

---

## Usage

```python
python index.py url 
```

```python
(example) python index.py https://www.google.com.br
```

Parameters and Options

| Parameters | Description  |  Required  |
|----------------|----------|----------|
| target_url | The target URL to be scanned. Example: http://example.com   | Yes   |
| attacker-url | URL where exfiltrated data will be sent. Default is http://localhost:5000   | Optional |
| safe-mode | Enables Safe Mode, which disables aggressive or potentially disruptive tests.   | Optional |
| help | Displays the help message with usage instructions.   | Optional |

---
## License
---
Licensed under the [MIT License](LICENSE).
**Free Software, Hell Yeah Baby!**
