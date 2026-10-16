\# Lab 5: Static Code Analysis



\*\*Name:\*\* Siri S S  

\*\*SRN:\*\* PES1UG24CS627  

\*\*Project:\*\* Wildlife Sightings



\## Issues Identified and Fixed



| No. | Tool | Issue | Fix Applied |

|---|---|---|---|

| 1 | Bandit | Possible SQL injection from string-formatted SQL | Used parameterized SQL queries |

| 2 | Bandit | Weak MD5 hash | Replaced MD5 with SHA-256 |

| 3 | Bandit | Use of assert for runtime checking | Replaced assert with an explicit runtime check |

| 4 | Pylint | Mutable default argument | Used None and initialized the dictionary inside the function |

| 5 | Pylint | Missing docstrings | Added module and function docstrings |

| 6 | Pylint / Flake8 | Naming and formatting violations | Used snake\_case names and corrected formatting |



\## Verification



\- Pylint score: 10.00/10

\- Bandit: No issues identified

\- Flake8: No reported violations

