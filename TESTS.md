# Tests

At the minimum, tests should evaluate the behavior that most closely mimicks what the user experiences.

This means that test suites which don't evaluate integration behavior are bound to permit the release of regressions into production environments.

Test suites without unit tests will increase the time it takes to assess how changes to code have altered the end behavior. While this can be permissable for trivial code sections it will result in an future unwillingness to change or improve the codebase.

Finally, test suites where compliance isn't enforced results in developers releasing changes without testing the code comprehensively.