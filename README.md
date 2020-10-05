# Caesar cipher encode/decode cli tool

## Install

* clone this repo
* `cd caesar-cipher`
* `npm i`

## Usage

CLI tool should accept 4 options (short alias and full name):

1.  **-s, --shift**: a shift
2.  **-i, --input**: an input file
3.  **-o, --output**: an output file
4.  **-a, --action**: an action encode/decode

For exit tool in interactive mode just press *Ctrl-D* or *Ctrl-C*

## Usage examples with test data

```

node index.js -a decode -s 7 -i test-dec-7.txt -o test-enc-7.txt
node index.js -a encode -s 7 -i test-enc-7.txt -o test-dec-7.txt

```
