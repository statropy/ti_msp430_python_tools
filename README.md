![CI](https://github.com/statropy/ti_msp430_python_tools/workflows/CI/badge.svg)

# MSP430 Python Tools

Currently only supports Python 2.7

## Install

```
git clone https://github.com/statropy/ti_msp430_python_tools
cd ti_msp430_python_tools/python-msp430-tools
python setup.py install
```

## Program MSP-EXP430F5529LP

 * Hold down BSL button
 * Connect USB cable to host to power-on
 * Release BSL button
 * `python -m msp430.bsl5.hid_1 -e -P <filename>`
