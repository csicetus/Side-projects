# What
## Defination - Recipes app
A recipe is a set of instructions that describes how to prepare or make something, especially a dish of prepared food.

## Function
+ Enter a name, a description with the steps
+ Have pictures
+ Have some ranking for difficulty and quality
+ Add the time needed
+ Have different steps with a picture for each
+ Store them local storage(refresh page will still be there)
+ All steps above can be changed

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
### Add advance button click event
Operator(AC): clear txt and store array

Operator(DEL): delete last str of txt
