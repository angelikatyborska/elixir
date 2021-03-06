# Exercism Elixir Track

![build status](https://travis-ci.org/exercism/elixir.svg?branch=master)

Exercism Exercises in Elixir

## Setup

The exercises currently target Elixir >= 1.6 and Erlang/OTP >= 20. Detailed
installation instructions can be found at
[http://elixir-lang.org/install.html](http://elixir-lang.org/install.html).

## Testing

---

> It is recommended to test BEFORE submitting a PR.  It will test your submission, ensure
> that the repository builds as a whole, and help guard against unintentional, unrelated changes.

---

### Test All Assignments

To test all of the assignments against their example solution, you can run `bin/test_exercises.sh`:

```shell
$ ./bin/test_exercises.sh
Testing: accumulate -- Pass
Testing: acronym -- Pass
...
Testing: zipper -- Pass
--------------------------------------------------------------------------------
93/93 tests passed.
```

This will take some time.

### Test Specific Assignment

Go in the the specific exercise directory, run `mix test` to test an individual assignment:

```shell
cd exercises/$EXERCISE_NAME
mix test
```

### Testing the Build

TravisCI is used to test the build against different environments.

TravisCI's current testing routine can be found in [.travis.yml](https://github.com/exercism/elixir/blob/master/.travis.yml)

## Contributing Guide

For an in-depth discussion of how exercism language tracks and exercises work, please see [CONTRIBUTING.md](https://github.com/exercism/elixir/blob/master/CONTRIBUTING.md)
