## checkout a specific version of a file from a past commit

To do so, find the commit hash in the `git log` or on github.
The below example checks out a tex file and creates a different file with its content.

```bash
git show 09078b4351e4750724f8f63fb4d0e2903c9d35e6:myfile.tex > myfile_old.tex
```
Now one could use latexdiff to create a diff version.
