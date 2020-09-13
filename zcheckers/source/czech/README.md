# CZECH - Comprehensive Z-machine Emulation CHecker

Czech is a set of tests to determine whether a Z-Machine interpreter is compliant with the Z-Machine specification. It is designed to check against the 1.0 version of the specification, although there are some fixes in place to check for conformance with the 1.1draft7 specification.

As of version 0.8, czech runs 425 tests under the version 5 generation of story files. As part of this operation, czech is designed to give information about which tests failed, to make it easy to debug problems with a specific interpreter.

The general usage is:

* Compile the `czech.inf` file to some story file version [-v3|-v4|-v5|-v8]
* Run your interpreter on czech.z[3458].
* Examine the output.
* Compare to czech.out[3458] with a file comparison tool.

It's important to note that header information *will* be different for different interpreters, platforms, and so on.

You can see the `czech.inf` for usage notes, such as how to skip sets of tests. This will also give you some information on how to find out which test failed.
