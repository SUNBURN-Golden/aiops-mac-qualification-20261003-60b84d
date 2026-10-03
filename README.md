# AIOPS Mac qualification fixture

This private repository is a disposable fixture for verifying the Mac application.
It is independent of all product repositories and existing VM work.

`arithmetic.py` currently provides `add(a, b)`.
Run validation with `python3 -m unittest discover -s tests -v`.

Requested qualification deliverable: implement `multiply(a, b)` for integer inputs, including positive, negative and zero cases; add unit tests for these cases; document usage in this README. Preserve the existing add function and passing tests. No dependencies, product rollout, account changes or service configuration are needed.
