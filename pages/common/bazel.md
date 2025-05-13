# bazel

> Open-source build and test tool similar to Make, Maven, and Gradle.
> More information: <https://bazel.build/reference/command-line-reference>.

- Build a specific target in the workspace:

`bazel build {{//path/to/package:target}}`

- Remove output files and stop the Bazel server if running:

`bazel clean`

- Stop the Bazel server:

`bazel shutdown`

- Display runtime information about the Bazel server:

`bazel info`

- Display help about available commands:

`bazel help`

- Display version information:

`bazel version`
