This is a test suite for C++ refactoring tools.  It consists of
a set of source files with comments marking different locations
in the code where a refactoring could be tested.

Over time, I've tried to add runtime assertions to the code to
give an additional level of testing around the refactored area.
While these assertions help to verify the validity of a refactoring
applied by a tool, the pass or fail of a test case is up to the
person invoking the refactoring tool and examining the diffs.

In general, when evaluating results from a refactoring tool,
you should treat the tool as skeptically as you would treat
any other programmer on your team.  If you wouldn't accept a
set of diffs from a human, then you shouldn't accept those
same diffs from a computer.

The original release of the test suite is described
[in this blog post](http://legalizeadulthood.wordpress.com/2010/02/02/c-refactoring-tools-test-suite-available/).

# [How To Contribute](Contributing.md)

# Results

## [Summary Results](SummaryResults.md)

## Current Products

- [CLion CL-140-1221.2](results/CLionResults.md)
- [clang-modernize 3.5.0](results/ClangModernizeResults.md)
- [ReSharper for C++ 10.0.2](results/ReSharperCppResults.md)
- [Visual AssistX 10.5.1738.0](results/VisualAssistXResults.md)
- [Visual Studio 2015](results/VisualStudio2015Results.md)

## Unknown Results

- [Code::Blocks](http://www.codeblocks.org/)
- [Eclipse CDT](https://eclipse.org/cdt/)
