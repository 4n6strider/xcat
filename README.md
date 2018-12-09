# XCat

![](https://travis-ci.com/orf/xcat.svg?branch=master)
![](https://img.shields.io/pypi/v/xcat.svg)
![](https://img.shields.io/pypi/l/xcat.svg)
![](https://img.shields.io/pypi/pyversions/xcat.svg)

XCat is a command line tool to exploit and investigate blind XPath injection vulnerabilities.

It supports an large number of features:

- Auto-selects injections (run `xcat injections` for a list)

- Detects the version and capabilities of the xpath parser and 
  selects the fastest method of retrieval

- Built in out-of-bound HTTP server
    - Automates XXE attacks
    - Can use OOB HTTP requests to drastically speed up retrieval

- Custom request headers and body

- Built in REPL shell, supporting:
    - Reading arbitrary files
    - Reading environment variables
    - Listing directories
    - Uploading/downloading files (soon TM)

For complete read the documentation here: https://xcat.readthedocs.io/en/latest/

## Install

Run `pip install xcat`

**Requires Python 3.7**. You can easily install this with [pyenv](https://github.com/pyenv/pyenv): 
`pyenv install 3.7.1`

## Example application

There is a complete demo application you can use to explore the features of XCat. 
See the README here: https://github.com/orf/xcat_app
 