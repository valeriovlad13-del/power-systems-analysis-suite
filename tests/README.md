# Calculation Regression Tests

This folder will hold independent calculation fixtures and regression tests as modules are audited.

Each test case should capture:
- module/calculator identifier
- input values and units
- expected result and units
- calculation source or independent derivation
- tolerance and reason for using it
- date/status verified

Do not copy expected outputs from the calculator under test without an independent calculation. Include common nominal cases, boundary inputs, invalid inputs, and domain-specific edge cases. Browser interaction tests should verify that controls update outputs, tabs work, and output is accessible on narrow screens.

Current status: test harness and individual cases have not yet been added.
