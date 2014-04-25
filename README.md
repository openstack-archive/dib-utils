Standalone tools related to diskimage-builder
=============================================

These tools were originally part of the diskimage-builder project, but they have
uses outside of that project as well.  Because disk space is at a premium in
base cloud images, pulling in all of diskimage-builder and its dependencies just to
use something like dib-run-parts is not desirable.  This project allows consumers
to use the tools while pulling in only one small package with few/no additional
dependencies.
