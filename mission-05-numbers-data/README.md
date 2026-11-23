# Mission 5 — Numbers and data
## 1. Task / objective
Convert decimal, binary and hexadecimal values by hand and in Python, build a converter, and explain text encoding.
## 2. Work completed
### Task 5.1 — Manual conversions
| Question | Working and answer |
|---|---|
| Decimal 13 to binary | 13 ÷ 2 remainders from last: 1,1,0,1 → `1101₂` |
| Decimal 25 to binary | 25 ÷ 2 remainders: 1,0,0,1 → `11001₂` |
| Binary 1010 to decimal | 1×8 + 0×4 + 1×2 + 0×1 = `10₁₀` |
| Binary 1101 to decimal | 1×8 + 1×4 + 0×2 + 1×1 = `13₁₀` |
| Hexadecimal A to decimal | A = 10 → `10₁₀` |
| Hexadecimal 1F to decimal | 1×16 + 15×1 = `31₁₀` |
| Binary 1111 to hexadecimal | 1111 is F in hexadecimal → `F₁₆` |

### Task 5.2 — Python verification
| Expression | Result | Matches manual result? |
|---|---|---|
| `bin(13)`, `bin(25)` | `0b1101`, `0b11001` | Yes |
| `int('1010', 2)`, `int('1101', 2)` | `10`, `13` | Yes |
| `hex(13)`, `hex(25)` | `0xD`, `0x19` | Yes; 25 decimal is 19 in hexadecimal |
| `int('A', 16)`, `int('1F', 16)` | `10`, `31` | Yes |

### Task 5.3 — Number converter
`number_converter.py` asks for a decimal integer and prints binary and hexadecimal strings. Tests:
| Test number | Binary | Hexadecimal |
|---|---|---|
| 13 | `0b1101` | `0xd` |
| 25 | `0b11001` | `0x19` |
| 255 | `0b11111111` | `0xff` |

`bin(number)` converts an integer to binary with a `0b` prefix. `hex(number)` converts it to hexadecimal with a `0x` prefix.

### Task 5.4 — Text encoding
- Decimal ASCII code for uppercase A: `65`.
- Decimal ASCII code for lowercase a: `97`.
- Encoding standards give text characters agreed numeric representations so systems can store and exchange text consistently. UTF-8 can represent characters beyond basic ASCII.
- Example character outside basic ASCII: `₹` or `A` in a different script, for example `आ`.

## 3. Commands / tools used
`python3`, `python3 number_converter.py`, `bin()`, `hex()`, `int()`, and `input()`.
## 4. My understanding
Bits hold binary values and bytes group eight bits. Positional bases determine a value's meaning. Encoding maps characters to numeric codes so text is stored consistently.
## 5. Difficulties faced
No major difficulties.
## 6. How I resolved them
Not applicable.
## 7. Evidence / files
`number_converter.py`, manual calculations, Python verification and encoding notes in this README.
## 8. Commit details
Commit: `Build number converter and practise data representation`; pushed to GitHub.
