
# Mission 5 — Numbers and Data

## Task 5.1 — Convert numbers by hand

### Decimal 13 to binary

13 ÷ 2 = 6 remainder 1  
6 ÷ 2 = 3 remainder 0  
3 ÷ 2 = 1 remainder 1  
1 ÷ 2 = 0 remainder 1  
Reading the remainders from bottom to top: **1101₂**

### Decimal 25 to binary

25 ÷ 2 = 12 remainder 1  
12 ÷ 2 = 6 remainder 0  
6 ÷ 2 = 3 remainder 0  
3 ÷ 2 = 1 remainder 1  
1 ÷ 2 = 0 remainder 1  
Reading the remainders from bottom to top: **11001₂**

### Binary 1010 to decimal

1 × 2³ + 0 × 2² + 1 × 2¹ + 0 × 2⁰  
= 8 + 0 + 2 + 0  
= **10₁₀**

### Binary 1101 to decimal

1 × 2³ + 1 × 2² + 0 × 2¹ + 1 × 2⁰  
= 8 + 4 + 0 + 1  
= **13₁₀**

### Hexadecimal A to decimal

A₁₆ = 10₁₀

### Hexadecimal 1F to decimal

1 × 16¹ + 15 × 16⁰  
= 16 + 15  
= **31₁₀**

### Binary 1111 to hexadecimal

1111₂ = 8 + 4 + 2 + 1 = 15₁₀  
15₁₀ = **F₁₆**

## Task 5.2 — Verify using Python

| Python expression | Result | Matches Task 5.1? |
|---|---|---|
| `bin(13)` | `0b1101` | Yes, 1101₂ |
| `bin(25)` | `0b11001` | Yes, 11001₂ |
| `int("1010", 2)` | `10` | Yes, 10₁₀ |
| `int("1101", 2)` | `13` | Yes, 13₁₀ |
| `hex(15)` | `0xf` | Yes, F₁₆ |
| `int("A", 16)` | `10` | Yes, 10₁₀ |
| `int("1F", 16)` | `31` | Yes, 31₁₀ |

## Task 5.3 — Number converter

| Input | Binary output | Hexadecimal output |
|---|---|---|
| 5 | `0b101` | `0x5` |
| 10 | `0b1010` | `0xa` |
| 15 | `0b1111` | `0xf` |

`input()` gets the number, `int()` makes it an integer, and `bin()` and `hex()` convert it.

## Task 5.4 — How is text stored?

- Uppercase `A`: 65
- Lowercase `a`: 97
- Character outside basic ASCII: `₹`

A computer needs an encoding standard to assign numbers to characters so it can store and display text consistently. UTF-8 supports characters such as `₹` that basic ASCII does not include.

## 1. Task / objective

Convert numbers between decimal, binary and hexadecimal, check them with Python, make a converter, and learn about text encoding.

## 2. Work completed

I completed Tasks 5.1–5.4 above and made the number_converter.py program.

## 3. Commands / tools used

- Python interactive environment — checked the number conversions.
- python3 number_converter.py — ran the converter.
- input() and int() — received the number and changed it to an integer.
- bin() and hex() — converted the number to binary and hexadecimal.
- Visual Studio Code — edited the README and Python file.

## 4. My understanding

Binary uses 0 and 1. Hexadecimal uses base 16. Python's bin() and hex() functions help convert numbers. Text encoding gives characters numbers so a computer can store and display them.

## 5. Difficulties faced

I was confused about where to write the answers for each task.

## 6. How I resolved them

I kept the answers and converter in the Mission 5 folder and used Python to check the conversions.

## 7. Evidence / files

- README.md has the calculations, Python checks and text-encoding notes.
- number_converter.py is the converter program.

## 8. Commit details

Commit message: Build number converter and practise data representation

The Mission 5 work was pushed to GitHub.
