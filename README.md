This repository uses a YAML file to generate custom NDcPP test plans.

Follow these steps to generate a custom test plan:

1. Select the 'Use this template' button (must be logged in) and create a new repository.
2. Check your repository permissions by going to Settings>Actions>WorkFlow Permissions> select 'Read and write' then save.
3. Delete any .adoc SFRs files from the v3.0 directories that you do not want included in your test plan. There are multiple ways execute this step, (i.e., Git CLI, your local repository, in your browser).
4. Select the 'Actions' button from the menu.
5. Select the 'Combine Asciidoc, Convert to HTML, and Commit' workflow.
6. Select 'Run workflow'. You can watch the status of the workflow as it runs (30 to 60 seconds typically).
7. Return to your repository's main page and download the 'combined-testplan.adoc' and/or 'testplan.html' documents.

NOTE: You may consider creating a new branch for each custom test plan you want to generate.
