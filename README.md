# Code Quality Tools

A list of code quality tools and test frameworks for editors and CI environments. If there is anything missing, please submit a pull request.

## Bash

#### Static Analysis

- [shellcheck](https://github.com/koalaman/shellcheck) - Warnings and suggestions for bash/sh shell scripts.

#### Testing

- [assert.sh](https://github.com/lehmannro/assert.sh) - Bash unit testing framework.
- [bash_test_tools](https://thorsteinssonh.github.io/bash_test_tools/) - For testing executables in a shell environment.
- [bash_unit](https://github.com/pgrange/bash_unit) - Bash unit testing enterprise edition framework.
- [bashtest](https://github.com/pahaz/bashtest) - A UNIX command-line tool for the testing bash/shell utilites.
- [bats](https://github.com/sstephenson/bats) - Bash Automated Testing System.
- [epoxy](https://github.com/spbnick/epoxy) - A flexible Bash test framework.
- [roundup](https://github.com/bmizerany/roundup) - Eliminate bugs and weeds from shell scripts.
- [shUnit2](https://github.com/kward/shunit2) - An xUnit based unit test framework for Bourne based shell scripts.

## CSS

- [scss-lint](https://github.com/brigade/scss-lint) - Configurable tool for writing clean and consistent SCSS.
- [stylelint](https://stylelint.io/) - A mighty, modern CSS linter.

## Docker

- [dockerfile_lint](https://github.com/projectatomic/dockerfile_lint) - A rule based linter for Dockerfiles.
- [dockerlint](https://github.com/RedCoolBeans/dockerlint) - Linting tool for Dockerfiles.
- [hadolint](https://github.com/hadolint/hadolint) - Haskell Dockerfile Linter

## Go

#### Static Analysis

- [errcheck](https://github.com/kisielk/errcheck) - Check for unchecked errors in go programs.
- [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) - Manage Go import lines.
- [golint](https://github.com/golang/lint) - A linter for Go source code.
- [gometalinter](https://github.com/alecthomas/gometalinter) - Concurrently run Go lint tools and normalise their output.
- [misspell](https://github.com/client9/misspell/) - Correct commonly misspelled English words in source files.

#### Editor Support

- [go-plus](https://atom.io/packages/go-plus) - Go support for Atom.
- [GoSublime](https://github.com/DisposaBoy/GoSublime) - Go support for Sublime Text 3.
- [vim-go](https://github.com/fatih/vim-go) - Go support for Vim.

## Java

- [PMD](https://pmd.github.io/) - Static code analyzer.

## Javascript

#### Static Analysis

- [coffeelint](http://www.coffeelint.org/) - A style checker that keeps CoffeeScript code clean and consistent.
- [ESLint](https://eslint.org/) - Javascript linting.
- [JSHint](http://jshint.com/) - A Static Code Analysis Tool for JavaScript.
- [TSLint](https://palantir.github.io/tslint/) - An extensible linter for the TypeScript language.

## PHP

#### Static Analysis

- [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) - Code violation checks and corrections.
- [PHPMD](https://phpmd.org/) - Mess detector for potential code issues.

#### Testing

- [phpunit](https://phpunit.de/) - A programmer-oriented testing framework for PHP.

#### Code Coverage

- [php-codacy-coverage](https://github.com/codacy/php-codacy-coverage) - Codacy support for PHP.

## Python

#### Static Analysis

- [flake8](https://pypi.python.org/pypi/flake8) - A modular source code checker for pep8, pyflakes, etc.
- [pep8](https://pypi.python.org/pypi/pep8) - Python style guide checker.
- [pycodestyle](https://pypi.python.org/pypi/pycodestyle) - Checks Python code against some style conventions.
- [pyflakes](https://pypi.python.org/pypi/pyflakes) - Checks Python source files for errors.

#### Code Coverage

- [python-codacy-coverage](https://github.com/codacy/python-codacy-coverage) - Python support for Codacy.

## Ruby

#### Static Analysis

- [bigfiles](https://github.com/apiology/bigfiles) - Tool to find the largest source files in your project.
- [Brakeman](https://github.com/presidentbeef/brakeman) - A static analysis security vulnerability scanner for Rails apps.
- [bunder-audit](https://github.com/rubysec/bundler-audit) - Patch-level verification for Bundler.
- [Bullet](https://github.com/flyerhzm/bullet) - Help to kill N+1 queries and unused eager loading.
- [cane](https://github.com/square/cane) - Code quality threshold checking as part of your build.
- [dawnscanner](https://github.com/thesp0nge/dawnscanner) - Static analysis security scanner.
- [flay](https://github.com/seattlerb/flay) - Analyzes code for structural similarities.
- [flog](https://github.com/seattlerb/flog) - Flog reports the most tortured code in an easy to read pain report.
- [haml-lint](https://github.com/brigade/haml-lint) - Tool for writing clean and consistent HAML.
- [laser](https://github.com/michaeledgar/laser) - Static analysis and style linter for Ruby.
- [pelusa](https://github.com/codegram/pelusa) - Static analysis lint tool.
- [punchlist](https://github.com/apiology/punchlist) - Counts the number of 'todo' comments in your code.
- [quality](https://github.com/apiology/quality) - Runs quality checks on your code over time.
- [querly](https://github.com/soutaro/querly) - Query Method Calls from Ruby Programs.
- [rack-mini-profiler](https://github.com/MiniProfiler/rack-mini-profiler) - Profiler for development and production Ruby rack apps.
- [Rails Best Practices](https://github.com/flyerhzm/rails_best_practices) - Code metric tool to check the quality of Rails code.
- [Reek](https://github.com/troessner/reek) - Code smell detector for Ruby.
- [Rubocop](https://github.com/bbatsov/rubocop) - Ruby static code analyzer.
- [rubrowser](https://github.com/emad-elsaid/rubrowser) - A visualizer for Ruby code.
- [rubycritic](https://github.com/whitesmith/rubycritic) - Ruby code quality reporter.
- [sandi-meter](https://github.com/makaroni4/sandi_meter) - Static analysis tool for checking Ruby code for Sandi Metz' rules.
- [traceroute](https://github.com/amatsuda/traceroute) - Find unused routes and controller actions for Rails apps.

#### Code Coverage

- [coveralls-ruby](https://github.com/lemurheavy/coveralls-ruby) - Coveralls support for Ruby.
- [rcov](https://github.com/relevance/rcov) - Code coverage for Ruby.
- [ruby-codacy-coverage](https://github.com/codacy/ruby-codacy-coverage) - Codacy support for Ruby.
- [simplecov](https://github.com/colszowka/simplecov) - Code coverage for Ruby.

## Swift

- [SwiftLint](https://github.com/realm/SwiftLint) - A tool to enforce Swift style and conventions.
