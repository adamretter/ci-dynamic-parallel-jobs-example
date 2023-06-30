# ci-dynamic-parallel-jobs-example
GitHub allows you to execute upto 256 jobs via Matrix. You can construct the Matrix dynamically based on output from another Job (or Step).

I wanted to see if I could validate XML files in parallel. This is based on a simple example I found here: https://dev.to/slashgear_/github-action-how-to-parallelize-tests-dynamically-by-folder-3hen

## TODO:
1. Work out the best way to process XML files in batches. e.g. if we have 5,000 XML files, and we can only have upto 256 parallel jobs, how best to batch those XML files across the available jobs?

