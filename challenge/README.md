# Challenges

A collection of debugging exercises across several languages. Each file ships
with working logic but contains one or more bugs to identify and fix while
preserving the original intent. The goal is to read unfamiliar code, reason
about its expected behaviour, and correct it without rewriting it.

## Challenges

| File | Language | Description |
| --- | --- | --- |
| [`0-fizzbuzz.py`](0-fizzbuzz.py) | Python | Print numbers from 1 to N with the FizzBuzz substitutions. |
| [`1-print_square.js`](1-print_square.js) | JavaScript | Print a square of `#` whose size is the first argument. |
| [`2-sort.rb`](2-sort.rb) | Ruby | Sort integer arguments in ascending order (insertion sort). |
| [`3-user.py`](3-user.py) | Python | `User` model with a UUID id and an MD5-hashed password. |
| [`4-delete_dnodeint/`](4-delete_dnodeint/) | C | Delete a node at a given index in a doubly linked list. |

## Requirements

| Language | Tooling |
| --- | --- |
| Python | Python 3 |
| JavaScript | Node.js |
| Ruby | Ruby |
| C | gcc, compiled with `-Wall -Werror -Wextra -pedantic` |

## Usage

```bash
# Python
python3 0-fizzbuzz.py 89
python3 3-user.py

# JavaScript
node 1-print_square.js 4

# Ruby
ruby 2-sort.rb 5 2 8 1

# C
cd 4-delete_dnodeint
gcc -Wall -Werror -Wextra -pedantic *.c -o dlist && ./dlist
```

## Author

JAuxance
