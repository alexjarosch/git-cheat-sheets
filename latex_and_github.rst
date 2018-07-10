Latex Git Workflow
==================
Here I outline the basic workflow for collaborating on LaTeX documents that works for me.

Basic concepts
--------------
- Write each sentence in your LaTeX document in a separate line. This helps git to understand your commits
- Consider the 'master' branch as the document version you are ready to submit/publish
- Each chapter/section is considered to be a "feature" that is developed on its own branch
- Each collaborator maintains her/his own BibTeX database

Start a repository
------------------
Simply create a repository on your favourite git hosting service and use a .gitignore tuned for LaTeX documents. Place in your .tex file along with non-standard style sheets from your publisher (this helps everybody to have the same style sheets).

Also commit the BibTeX database you are using. In the TeX document you can simply use ``\bibliography{bibtex_file1,bibtex_file2,bibtex_file3}`` with all database files listed .


