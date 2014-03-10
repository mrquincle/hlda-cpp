# Hierarchical Latent Dirichlet Allocation (HLDA)

The link for the original repository can be found at http://code.google.com/p/hlda-cpp/. This repository is subsequently forked from https://github.com/xch91/hlda-cpp.

This is a C++ re-implementation of David Blei's Hierarchical Latent Dirichlet Allocation (HLDA) topic modeling software.
The model finds a hierarchy of topics, where the data determines the structure of the hierarchy. The depth of the hierarchy is fixed.

The HLDA model is described in two of David Blei's papers:

* http://www.cs.princeton.edu/~blei/papers/BleiGriffithsJordanTenenbaum2003.pdf
* http://www.cs.princeton.edu/~blei/papers/BleiGriffithsJordan2009a.pdf

David Blei's implementation of HLDA in C:

* http://www.cs.princeton.edu/~blei/downloads/hlda-c.tgz

Dependencies:

This code depends on the GSL GNU Scientific Library:
 * http://www.gnu.org/software/gsl/

## Installation

On Ubuntu it is simple

    sudo apt-get install libgsl0-dev
    make

## Usage

Input:

The input is in the following format:

    [number of unique words] [word id] : [count] ...

There is a sample test file in the testdata directory, along with a settings file for this test data.

## License

License is Apache 2.0.
Copyrights are as indicated in the individual files, but apparently mostly attributed to Google Inc.
