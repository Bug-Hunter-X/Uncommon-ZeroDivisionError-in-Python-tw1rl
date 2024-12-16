# Uncommon ZeroDivisionError in Python

This repository demonstrates a subtle ZeroDivisionError in Python that may be missed during testing due to the unusual combination of inputs. The error occurs when both inputs to the `function_with_uncommon_error` are zero, resulting in division by zero even though there are checks for individual zeros.