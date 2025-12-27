> Notes i've taken for the book are available in [notes](https://github.com/dheeraj120501/zero-to-production-in-rust/tree/notes) branch.

## Zero to production in Rust

This is code for my walkthrough on zero to production rust book.

### CI/CD pipelines

> This code for pipelines are taken directly from [here](https://gist.github.com/LukeMathWalker/5ae1107432ce283310c3e601fac915f3).

Github actions is used to run the pipelines.

`audit.yml`: This contains pipeline code for checking vulnerabilities in dependencies.

`checks.yml`: This contains pipeline code for running basic sanity checks (static and dynamic code analysis) like test, linting, formatting checks.

> To run pipelines locally try [act](https://github.com/nektos/act).

### Credits

1. [Zero to production in rust book](https://www.zero2prod.com/index.html)
2. [LukeMathWalker for Pipeline as code for GH actions](https://gist.github.com/LukeMathWalker/5ae1107432ce283310c3e601fac915f3)
