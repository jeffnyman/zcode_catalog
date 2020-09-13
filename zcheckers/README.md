# Z-Checkers

These programs are intended to exercise an interpreter such that the interpreter can be verified as functioning according to the Z-Machine specification. As far as can be determined, the programs are in the public domain or made freely available with no restrictions. Copyrights are retained by the original authors where such copyrights are noted.

**crashme**
This tool provides self-modifying reproducing z-code. Essentially it generates random junk to see how the interpreter behaves. A good interpreter should not crash except on fatal errors. This tool was written by Evin Robertson in 1999.

**czech**
Referred to as the Comprehensive Z-machine Emulation CHecker, this tool provides a set of tests to determine whether a Z-Machine interpreter is compliant with the Z-Machine 1.0 specification. This tool was written by Amir Karger in 2003.

**TerpEtude**
Referred to as "etude", this tool exercises the Z-Machine emulator to determine proper behavior but does not test error-handling. This tool was written by Andrew Plotkin in 1997.

**gntests**
This tool provides assorted tests for checking the proper handling of fonts, accents, input codes, colors, header, and timed input. All of the checks are to verify conformace to the 0.9 version of the Z-Machine specification. This is actually a bit of a weaker version of TerpEtude. This tool was originally written by Graham Nelson as a collection of sample programs and unified by Andrew Plotkin in 1997.

**praxix**
This tool provides the equivalent of unit tests for an interpreter. This was written by Andrew Plotkin and Dannii Willis in 2019.

**random**
This tool goes by the title "Inform Randomization Test v1.0." Provided are assorted tests for checking the performance of an interpreter's random number generator. This was written by David Griffith in 2002.

**strictz**
This tool tests an interpreter's error-checking by attempting to cause all possible non-fatal errors. This tool was written by Torbjorn Andersson in 1998.

**unicode**
This tool goes by the title "Unicode Test v1.0" and is designed to create assorted unicode characters. This tool was written by David Kinder in 2002.
