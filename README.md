# dwl
discriminative word lexicon built on top of cnn

# Building instructions

You will need to download the [CNN neural network library](https://github.com/clab/cnn). Add a symlink from the root of the repository to the root of CNN then do:

    mkdir build
    cmake .. -DEIGEN3_INCLUDE_DIR=/path/to/eigen
    make

# Data format

Use the [cdec parallel data format](http://www.cdec-decoder.org/guide/fast_align.html).

# Note

This isn't supported or anything, I just wanted an example of the model with CNN and thought it might be of interest for others.

