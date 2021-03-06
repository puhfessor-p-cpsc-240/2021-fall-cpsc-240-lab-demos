
# Lab Demos

This repository is just a collection of the demonstrations presented in lab, where applicable and/or useful.

Copyright Puh P

## Sub-Directories

Each subdirectory is its own demonstration and should contain all files needed for that demo. Use the Makefile inside to run building commands.

Students won't need to use the Makefile at the root of this repository. It's just for me. Feel free to study it for your own learning.

### libPuhfessorP.so

Some subdirectory demos make use of the libPuhfessorP shared object. However, those shared objects are setup to be ignored by git. Therefore, a simple clone of this repository might not work as-is.

You'll find each demo utilizing libPuhfessorP.so has a symlink inside that points to *libPuhfessorP.so* at the root of this repository. In turn, *libPuhfessorP.so* at the root of this repository is actually just another symlink which points to a specific version of that library.

It is that specific version that should be downloaded and placed at the root of this repository for the demos to work. For example, at the time of this writing the latest SO file is *libPuhfessorP.v0.11.2.so*, which can be downloaded from the [Deploy Repository](https://github.com/puhfessor-p-cpsc-240/libPuhfessorP-deploy). You may download older versions of the SO by sifting through the list of commits.

## Git Tags

You may notice this repository also contains "git tags". You can view them with the following command:

```git tag```

Git tags allow you to assign human-readable labels to specific commits in the repository. Usually, a tag might look like *v1.12.6*. In this class, we'll use git tags that correspond to the date we did something in lab, so you can better see the power of git with respect to looking back on the state of your repository at a previous point in time.

For example, you can see what this repo looked like after the first day we began our assembly demonstrations with the following command:

```git checkout 2021-09-02```

When you are finished, get back to the current state by checking out the master branch with:

```git checkout master```

## Topics Covered

This section contains topics that were already covered, as a reminder to myself.

* Pure assembly program

* Hybrid assembly program

* Hybrid assembly program utilizing *libPuhfessorP*

* Advanced Makefile with variables, phony targets, and a different target for each source/object pair, and the linking step.

* Integer math

* Register preservation

* Conditional jumps

* Local variables / Local array on the stack

* Hybrid function calls by value, with pointers, and with floats

* Addressing modes

## Topics to Cover

This section contains some future topics that will be covered if time permits.

### Unfinished Demos

The following demos still have things left (notes are inside their sub-folders):

* Nada








