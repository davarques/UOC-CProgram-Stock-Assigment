# Stock Notices

<img width="1200" height="300" alt="banner" src="https://github.com/user-attachments/assets/cbf41804-f6d8-42cc-a5a3-092e8b2d1698" />

Program in C for the UOC course Fundamentals of Programming.

## What it does

- Reads the stock of 6 equipment types from a text file.
- Creates a notice for each type with fewer than 5 units.
- Calculates the units to restock and the cost, using the average of the max and min prices.
- Prints the notices and the total restock cost, or `NO NOTICES.` if all types are above the minimum.

## Concepts used

Constants (`#define`), `typedef enum`, vectors, `for` loops, `if`, reading files with `fopen` and `fscanf`.

## How to run

1. Compile: `gcc main.c -o stock`
2. Run: `./stock`
3. Enter the file name when asked: `equip1.txt` or `equip2.txt`

## Example (equip1.txt)

```
MINIMUM STOCK NOTICES (1-DESKTOP, 2-LAPTOP, 3-PRINTER, 4-MONITOR, 5-KEYBOARD, 6-MOUSE)

EQUIPMENT - REQUIRED - RESTOCK COST [EUR]
3 - 2 - 350.00
5 - 5 - 137.00
1 - 1 - 775.15

TOTAL RESTOCK COST [EUR]: 1262.15
```
