# code-formal-verification-data
Source data and outputs of the code formal verification pipeline.

## source_code.zip

All the backend source code used as the input to the formal verification pipeline. 

Each project has three parts: A code dir that contains the source code; a document dir, which contains a table description in yaml format which is used to formalize the table structure; a `doc.md` file for system specifications.


## results.zip

Backend source code to be used as input for the formal verification pipeline. There are four projects (see names) and variants from them, each contains a single bug inside (named as project_nameVx). Each project contains the source code dir and the document dir (for the table description file only).

> To use the existing results for evaluation:
> 1. Unzip `results.zip`
> 2. Configure paths in `plot.sh` and `analyze.sh` from the pipeline repo to point to the output files
> 3. Install Lean version 4.17.0 to ensure compatibility with these results

> Note: If you plan to run the pipeline from scratch, you can use any version of Lean.