# Python LeetCode Solutions

A collection of my [LeetCode](https://leetcode.com/) problem solutions written in **Python**. Each problem lives in its own folder (named `<problem-number>-<problem-slug>`) containing the solution code and the original problem statement.

## 📋 Solved Problems

| # | Problem | Difficulty | Approach | Solution |
| :--: | --- | :--: | --- | :--: |
| 12 | [Integer to Roman](https://leetcode.com/problems/integer-to-roman) | 🟠 Medium | Greedy — map values to symbols from largest to smallest | [Code](./12-integer-to-roman/integer-to-roman.py) |
| 207 | [Course Schedule](https://leetcode.com/problems/course-schedule) | 🟠 Medium | Topological sort (Kahn's algorithm / BFS on in-degrees) | [Code](./207-course-schedule/course-schedule.py) |

**Total solved:** 2

## 📂 Repository Structure

```
.
├── 12-integer-to-roman/
│   ├── integer-to-roman.py   # Solution
│   └── README.md             # Problem statement
└── 207-course-schedule/
    ├── course-schedule.py    # Solution
    └── README.md             # Problem statement
```

## 🚀 Running a Solution

Each solution is implemented as a method inside a `Solution` class (LeetCode format). To run one locally, instantiate the class and call the method:

```python
# Example: 12-integer-to-roman/integer-to-roman.py
from importlib import import_module

sol = Solution()
print(sol.intToRoman(1994))   # -> "MCMXCIV"
```

> **Note:** Some solutions (e.g. `course-schedule.py`) use `List` and `deque`. When running outside LeetCode, add the imports:
> ```python
> from typing import List
> from collections import deque
> ```

## 🛠️ Requirements

- **Python 3.x**

## 👤 Author

**Siddhesh Mishra** — [@sidm6599](https://github.com/sidm6599)

---

*This repository is updated as I solve more problems.*
