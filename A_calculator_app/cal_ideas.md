# What
## Defination - Wiki
An electronic calculator is typically a portable electronic device used to perform calculations, ranging from basic arithmetic to complex mathematics.

## Function
Basic function: + - * / 

Advanced function: DEL AC

# How - 3 steps
## 1. Get each buttons' values
### Button click event
Basic buttons(0-9): add value to txt

Special button(.): if '.' + '.', do nothing
## 2. Deal with operators
### Expand button click event
Basic operators(+-*/): push txt and operators, noted we should clean screen txt

Special operator(=): push txt and calculate result, noted we should clear the store array
## 3. Add advance functions
