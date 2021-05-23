# urlscan

automatically search and get results for urlscan.
the results are search results and dom, response and screenshot of a top page.

## Requirements

### python3

You need Python 3.
Also you may need Python 3.6 or later.

### packages

* python3-pip

### python packages

* defang
* python-dateutil
* pytz

## Installation

To install packages

```
$ sudo apt install python3-pip
```

To install python packages

```
$ pip3 install -r requirements.txt
```

## Usage

```
./urlscan.py --help
usage: urlscan.py [-h] [--hostname HOSTNAME] [--url URL] [--top TOP]
		  [--minimum-size MINIMUM_SIZE] [--strict-hostname]

optional arguments:
  -h, --help		show this help message and exit
  --hostname HOSTNAME	hostname
  --url URL		url
  --top TOP		how many result sorted recently? (default: 1)
  --minimum-size MINIMUM_SIZE	filter by minimum bytes in stats.dataLength.
  --strict-hostname	ex. example.com: doesn't match www.example.com when this options is true. (default: false)
```