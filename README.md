# Code Quality Demo

This project demonstrates a code-quality warning.

The code works correctly, but it contains:

- TODO comment
- FIXME comment
- Unused variable

## Expected

BUILD -> PASS
TESTS -> PASS
QUALITY -> WARNING

## Fix

Remove the TODO and FIXME comments and the unused variable.
