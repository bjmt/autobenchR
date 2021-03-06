# autobenchR 1.1.3

* Use `pryr::mem_change()` if memory profiling is not enabled
* Update output of `bench` runs to match `bench` update (no mean and max columns)

# autobenchR 1.1.2

* Renamed package autobench --> autobenchR

# autobenchR 1.1.1

* Forgot to export `note()`

# autobenchR 1.1.0

* New `note()` function: insert user notes in results during an `autobenchR` run

# autobenchR 1.0.0

* Improved markdown output
* Expanded description and function documentation

# autobenchR 0.0.4

* Results can now be output in markdown format
* After `end()` is called, `run()`, `skip()`, and `update()` will give errors if run
  before `begin()`

# autobenchR 0.0.3

* All output from benchmarked expressions is suppressed (i.e., `cat`, `print`)
* Error messages are saved
* Fixed memory always showing as bytes for `microbenchmark`/`rbenchmark`
* Printing session info is now optional

# autobenchR 0.0.2

* `units` option now works when using `rbenchmark`
* README now includes an `rbenchmark` example

# autobenchR 0.0.1

* Initial version
